931. Minimum Falling Path Sum | Medium
Given an n x n array of integers matrix, return the minimum sum of any falling path through matrix.

A falling path starts at any element in the first row and chooses the element in the next row that is either directly below or diagonally left/right. Specifically, the next element from position (row, col) will be (row + 1, col - 1), (row + 1, col), or (row + 1, col + 1).

Example 1:
Input: matrix = [[2,1,3],[6,5,4],[7,8,9]]
Output: 13
Explanation: There are two falling paths with a minimum sum as shown.

Example 2:
Input: matrix = [[-19,57],[-40,-5]]
Output: -59
Explanation: The falling path with a minimum sum is shown.
 
Constraints:
n == matrix.length == matrix[i].length
1 <= n <= 100
-100 <= matrix[i][j] <= 100


Solution: C++

class Solution {
 public:
  int minFallingPathSum(vector<vector<int>>& A) {
    const int n = A.size();

    for (int i = 1; i < n; ++i)
      for (int j = 0; j < n; ++j) {
        int mini = INT_MAX;
        for (int k = max(0, j - 1); k < min(n, j + 2); ++k)
          mini = min(mini, A[i - 1][k]);
        A[i][j] += mini;
      }

    return ranges::min(A[n - 1]);
  }
};