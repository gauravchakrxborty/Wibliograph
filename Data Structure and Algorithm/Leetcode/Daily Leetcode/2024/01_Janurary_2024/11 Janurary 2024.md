1026. Maximum Difference Between Node and Ancestor | Medium

Tree | Depth-First Search | Binary Tree

Given the root of a binary tree, find the maximum value v for which there exist different nodes a and b where v = |a.val - b.val| and a is an ancestor of b.

A node a is an ancestor of b if either: any child of a is equal to b or any child of a is an ancestor of b.


Example 1:
Input: root = [8,3,10,1,6,null,14,null,null,4,7,13]
Output: 7
Explanation: We have various ancestor-node differences, some of which are given below :
|8 - 3| = 5
|3 - 7| = 4
|8 - 1| = 7
|10 - 13| = 3
Among all possible differences, the maximum value of 7 is obtained by |8 - 1| = 7.


Example 2:
Input: root = [1,null,2,null,0,3]
Output: 3
 

Constraints:

The number of nodes in the tree is in the range [2, 5000].
0 <= Node.val <= 105


Solution: C++

class Solution {
public:
    int maxAncestorDiff(TreeNode* root) {
        int m = 0;
        dfs(root, m);
        return m;
    }

private:
    std::pair<int, int> dfs(TreeNode* root, int& m) {
        if (root == nullptr) {
            return {INT_MAX, INT_MIN};
        }

        auto left = dfs(root->left, m);
        auto right = dfs(root->right, m);

        int minVal = std::min(root->val, std::min(left.first, right.first));
        int maxVal = std::max(root->val, std::max(left.second, right.second));

        m = std::max({m, std::abs(minVal - root->val), std::abs(maxVal - root->val)});

        return {minVal, maxVal};
    }
};