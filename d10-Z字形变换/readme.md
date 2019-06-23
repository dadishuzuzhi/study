将一个给定字符串根据给定的行数，以从上往下、从左到右进行 Z 字形排列。

比如输入字符串为 "LEETCODEISHIRING" 行数为 3 时，排列如下：

用例
========================================================================
L   C   I   R
E T O E S I I G
E   D   H   N
之后，你的输出需要从左往右逐行读取，产生出一个新的字符串，比如："LCIRETOESIIGEDHN"。

请你实现这个将字符串进行指定行数变换的函数：

string convert(string s, int numRows);

示例 1:

输入: s = "LEETCODEISHIRING", numRows = 3
输出: "LCIRETOESIIGEDHN"
示例 2:

输入: s = "LEETCODEISHIRING", numRows = 4
输出: "LDREOEIIECIHNTSG"
解释:

L     D     R
E   O E   I I
E C   I H   N
T     S     G

a   f
b e G i
c   h
=========================================================================


执行用时 :328 ms, 在所有 JavaScript 提交中击败了11.40%的用户
内存消耗 :65.3 MB, 在所有 JavaScript 提交中击败了5.76%的用户

ask1比第一版少了一步维护二维数组的操作,减少了空间消耗,但是==========不知道为什么增大了时间消耗!!!!!!!!!
执行用时 :468 ms, 在所有 JavaScript 提交中击败了5.87%的用户
内存消耗 :49.2 MB, 在所有 JavaScript 提交中击败了13.34%的用户