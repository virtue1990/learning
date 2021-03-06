## 字符串

### 主要内容
1. 字符串循环移位
2. LCS最长递增子序列
3. 字符串全排列
4. Manacher算法
5. KMP模式串匹配（附：BM算法）
6. 三字母字符串组合


### 课程算法习题
1. 字符串循环左移
```
给定一个字符串S[0...N-1]，要求把S的前k 个字符移动到S的尾部，如把字符串“abcdef” 前面的2个字符
‘a’、‘b’移动到字符串的尾部，得到新字符串“cdefab”:即字符串循环 左移k。
解析：
  循环左移n+k位和K位的效果相同。
要求：
  时间负责度位1，空间复杂度为o(1)

```

2. LCS
```
定义：
  最长公共子序列，即Longest Common Subsequence
  一个序列S的任意删除若干个自负得到新序列T，则T叫做S的子序列
  两个序列X和Y的公共子序列中，长度最常的那个，定义为X和Y的最长公共子序列
  字符串13455和245576的最长公共子序列为455
  字符串acdfg和adfc的最长公共子序列为adf
  注意区别最长公共子串（要求连续）
```

2. 最大公共子序列的多解性：求所有的LCS

3. 字符串的全排列
```
给定字符串S[0,...，N-1]，设计算法，枚举S的全排列
解析：
  1. 用递归
```

4. 最长回文子串
```
给定字符串str，若字串s是回文串，称s为str的回文子串。设计算法，计算str的最长回文子串
```

5. KMP算法
```
字符串查找问题
  给定文本串和text和模式串pattern，从文本串中text找出模式串pattern的第一个位置
```

6. KMP应用，PowerString问题
```
给定一个长度为n的字符串S，如果存在一个字符串T，重复若干次T能够得到S，那么，S叫做周期串，T叫做
S的一个周期
eg：
  如:字符串abababab是周期串，abab、ab都 是它的周期，其中，ab是它的最小周期
设计一个算法，计算S的最小周期。如果S不 存在周期，返回空串
```

7. 三字母字符串组合
```
仅由三个字符A、B、C构成字符串，且字符串任意三个相邻元素不能完全相同。如 “ACCCAB”不合法，
“ABBCBCA”合法。求满足条件的长度为n的字符串个数；要求时间和空间复杂度不高于O(N)
```
