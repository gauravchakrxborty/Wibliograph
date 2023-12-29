**1335**. Minimum Difficulty of a Job Schedule | Hard

You want to schedule a list of jobs in d days. Jobs are dependent (i.e To work on the ith job, you have to finish all the jobs j where 0 <= j < i).You have to finish at least one task every day. The difficulty of a job schedule is the sum of difficulties of each day of the d days. The difficulty of a day is the maximum difficulty of a job done on that day. You are given an integer array jobDifficulty and an integer d. The difficulty of the ith job is jobDifficulty[i]. Return the minimum difficulty of a job schedule. If you cannot find a schedule for the jobs return -1.

Example 1:
Input: jobDifficulty = [6,5,4,3,2,1], d = 2
Output: 7
Explanation: First day you can finish the first 5 jobs, total difficulty = 6.
Second day you can finish the last job, total difficulty = 1.
The difficulty of the schedule = 6 + 1 = 7 

Example 2:
Input: jobDifficulty = [9,9,9], d = 4
Output: -1
Explanation: If you finish a job per day you will still have a free day. you cannot find a schedule for the given jobs.

Example 3:
Input: jobDifficulty = [1,1,1], d = 3
Output: 3
Explanation: The schedule is one job per day. total difficulty will be 3.
 

Constraints:
1 <= jobDifficulty.length <= 300
0 <= jobDifficulty[i] <= 1000
1 <= d <= 10

Sollution : 


Approach
1. Dynamic Programming:
The code solves the problem using dynamic programming, breaking it down into smaller, overlapping subproblems and storing intermediate results.

2. Key Idea:
dp[j] stores the minimum difficulty of the first j+1 jobs scheduled exactly in i+1 days.

3. Initialization:
Handles base cases: insufficient jobs for d days and equal jobs and days.
Initializes dp with the maximum difficulty encountered so far.

4. Iterative Calculation:
Uses nested loops to compute dp[j] for each day i and job j.
Iterates through possible day-job combinations to find the minimum difficulty.
Swaps dp arrays for efficient updates.

5. Optimal Result:
dp.back() holds the minimum difficulty to schedule all jobs in d days.

Time Complexity:
O(n^2 * d) due to nested loops.

Space Complexity:
O(n) for the two dp arrays.

Code : C++

class Solution {
public:
    int minDifficulty(vector<int>& jobDifficulty, int d) {
        int jobs = jobDifficulty.size();

        // Check if it's impossible to do at least 1 job every day
        if (jobs < d) 
            return -1;

        // Find the maximum difficulty among jobs
        int max_difficulty = *max_element(jobDifficulty.begin(), jobDifficulty.end()) + 1;

        // Initialize vectors to store difficulty for previous and current days
        vector<int> prv_day(jobs, max_difficulty), curr_day(jobs);

        // Iterate over each day
        for (int days = 0; days < d; ++days) {
            vector<int> stack;

            // Iterate over each job starting from the current day
            for (int i = days; i < jobs; i++) {
                // Calculate difficulty for the current day
                if (i > 0)
                    curr_day[i] = prv_day[i - 1] + jobDifficulty[i];
                else 
                    curr_day[i] = jobDifficulty[i];
                // Start fresh day with the first job as ith

                // Handle job dependencies and find minimum difficulty
                while (!stack.empty() && jobDifficulty[stack.back()] <= jobDifficulty[i]) {
                    int j = stack.back(); 
                    stack.pop_back();
                    curr_day[i] = min(curr_day[i], curr_day[j] - jobDifficulty[j] + jobDifficulty[i]);
                }
                
                // Update difficulty based on previous days
                if (!stack.empty()) {
                    curr_day[i] = min(curr_day[i], curr_day[stack.back()]);
                }

                // Add the current job to the stack
                stack.push_back(i);
            }

            // Update difficulty vectors for the next day
            swap(prv_day, curr_day);
        }

        // Return the minimum difficulty for the last day
        return prv_day[jobs - 1];
    }
};