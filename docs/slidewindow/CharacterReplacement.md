## 题目描述
给你一个仅由大写英文字母组成的字符串，你可以将任意位置上的字符替换成另外的字符，总共可最多替换 k 次。在执行上述操作后，找到包含重复字母的最长子串的长度。

注意：字符串长度 和 k 不会超过 104。

 

示例 1：

输入：s = "ABAB", k = 2
<br>输出：4
<br>解释：用两个'A'替换为两个'B',反之亦然。

<br>示例 2：
<br>输入：s = "AABABBA", k = 1
<br>输出：4
<br>解释：
<br>将中间的一个'A'替换为'B',字符串变为 "AABBBBA"。
子串 "BBBB" 有最长重复字母, 答案为 4。
## 解法
### 1 滑动窗口
[==>SOLUTION<==](https://leetcode-cn.com/problems/longest-repeating-character-replacement/solution/ti-huan-hou-de-zui-chang-zhong-fu-zi-fu-eaacp/)
## 代码
[CharacterReplacement.java](https://github.com/Marshal7cc/leetcode-java/blob/master/src/slidewindow/CharacterReplacement.java)

