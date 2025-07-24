[index](index.html)

#### Reviewed LeetCode Problems (for my personal reference)

- [brood0783 - 141. Linked List Cycle](https://github.com/brood0783/arai60/pull/2)
- [chanseok-lim - 141. Linked List Cycle](https://github.com/chanseok-lim/arai60/pull/10)
	- When checking two objects are the same, `is` should be used instead of `==`.
- [garunitule - 560. Subarray Sum Equals K](https://github.com/garunitule/coding_practice/pull/16)
- [garunitule - 200. Number of Islands](https://github.com/garunitule/coding_practice/pull/17)
	- Command Query Separation
	- Descriptive function/variable names
	- ["個人的な感覚、union find は現実的には多くの人が知っているし、知らなくても書かれれば読めるんですが、しかし、知らない同僚がいたとしても別に動揺しないというラインだと思いますね。"](https://github.com/garunitule/coding_practice/pull/17#discussion_r2170301165)
- [garunitule - 695. Max Area of Island](https://github.com/garunitule/coding_practice/pull/18)
- [garunitule - 323. Number of Connected Components in an Undirected Graph](https://github.com/garunitule/coding_practice/pull/19)
	- To avoid `RecursionError: maximum recursion depth exceeded while pickling an object.`, it makes sense to create a stack myself to perform DFS.
- [garunitule - 104. Maximum Depth of Binary Tree](https://github.com/garunitule/coding_practice/pull/21)
	- Cyclomatic Complexity, great engineers always come up with a very simple solution
	- Top down vs Bottom up
- [garunitule - 127. Word Ladder](https://github.com/garunitule/coding_practice/pull/20)
	- Shortest path -> BFS
- [garunitule - 111. Minimum Depth of Binary Tree](https://github.com/garunitule/coding_practice/pull/22)
	- Search for the shallowest leaf node -> BFS
- [h1rosaka - 49. Group Anagrams](https://github.com/h1rosaka/arai60/pull/16)
- [Kazuryu0907 - 1. Two Sum](https://github.com/Kazuryu0907/LeetCode_Arai60/pull/1)
- [Kazuryu0907 - 387. First Unique Character in a String](https://github.com/Kazuryu0907/LeetCode_Arai60/pull/2)
- [Kazuryu0907 - 560. Subarray Sum Equals K](https://github.com/Kazuryu0907/LeetCode_Arai60/pull/4)
- [plushn - 1. Two Sum](https://github.com/plushn/SWE-Arai60/pull/11)
- [ryosuketc - 322. Coin Change](https://github.com/ryosuketc/leetcode_arai60/pull/53)
	- Memoization with `functools.cache`
	- Two means of dynamic programming: memoization and tabulation
- [Ryotaro25 - 226. Invert Binary Tree](https://github.com/Ryotaro25/leetcode_first60/pull/71)
	- std::swap
	- Google Style Guide: Do not use using-directives (e.g., using namespace foo)
- [shintaroyoshida20 - 217. Contains Duplicate](https://github.com/shintaroyoshida20/leetcode/pull/32)
	- [MDN - Array.prototype.sort()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/sort)
		- "The time and space complexity of the sort cannot be guaranteed as it depends on the implementation."
- [tokuhirat - 322. Coin Change](https://github.com/tokuhirat/LeetCode/pull/40)
	- TIL: `math.isinf()`
- [tshimosake - 98. Validate Binary Search Tree](https://github.com/tshimosake/arai60/pull/18)
	- BST in-order traversal -> ascending (or correctly ordered) numbers
