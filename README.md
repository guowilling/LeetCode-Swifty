# LeetCode-Swift-Track

LeetCode 💖 Swift，攻克[数据结构](#数据结构)与[算法](#算法)。

**宣言**：~~早搞晚搞，迟早要搞，干就是了！~~ **Just Do IT！**

## 开始练习

1. [LeetCode 探索](https://leetcode-cn.com/explore/)

  - -> 选择一个「[数据结构](#数据结构)」或「[算法](#算法)」卡片

  - -> 学习相关概念

  - -> 提炼记录必要笔记

2. 打开 [LeetCodePlayground.playground](./LeetCodePlayground.playground) 练习步骤1）的卡片中的一道算法题

3. 在 LeetCode 测试并完成算法题的提交

4. 补充算法要点与简单描述

5. 单独提交 Swift 文件并更新 README 以便在 GitHub 查看

## 数据结构

数据结构是为算法服务的

- [数组](#数组) [`📔`](./Array/README.md)
- [字符串](#字符串)
- [链表](#链表) [`📔`](LinkedList/README.md)
- [栈](#栈) [`📔`](Stack/README.md)
- [队列](#队列)
- [散列表](#散列表)
- [二叉树](#二叉树)
- [堆](#堆)
- [跳表](#跳表)
- [图](#图)
- [Trie 树](#Trie-树)

### 数组

标题                                                                                               |        标签         | 描述                                                                                                                            |                              题解
:----------------------------------------------------------------------------------------------- | :---------------: | :---------------------------------------------------------------------------------------------------------------------------- | :----------------------------------------------------------:
[1\. 两数之和](https://leetcode-cn.com/problems/two-sum/)                                            |    `数组` `哈希表`     | 给定一个整数数组和目标值，找出和为目标值的那两个整数。                                                                                                   |              [Swift](./Array/001_TwoSum.swift)
[724\. 寻找数组的中心索引](https://leetcode-cn.com/problems/find-pivot-index/)                            |       `数组`        | 给定一个整数数组，找出「中心索引」                                                                                                             |          [Swift](./Array/724_FindPivotIndex.swift)
[747\. 至少是其他数字两倍的最大数](https://leetcode-cn.com/problems/largest-number-at-least-twice-of-others/) |       `数组`        | 查找数组中的最大元素是否至少是数组中每个其他数字的两倍。                                                                                                  | [Swift](./Array/747_LargestNumberAtLeastTwiceofOthers.swift)
[66\. 加一](https://leetcode-cn.com/problems/plus-one/)                                            |       `数组`        | 给定一个由**整数**组成的**非空**数组所表示的非负整数，在该数的基础上加一。                                                                                     |              [Swift](./Array/66_PlusOne.swift)
[498\. 对角线遍历](https://leetcode-cn.com/problems/diagonal-traverse/)                               |       `数组`        | 给定一个含有 M x N 个元素的矩阵（M 行，N 列），请以对角线遍历的顺序返回这个矩阵中的所有元素                                                                           |         [Swift](./Array/498_Diagonal_Traverse.swift)
[118\. 杨辉三角](https://leetcode-cn.com/problems/pascals-triangle/)                                 |       `数组`        | 给定一个非负整数 _numRows，_生成杨辉三角的前 _numRows_ 行                                                                                       |         [Swift](./Array/118_Pascal's_Triangle.swift)
[283\. 移动零](https://leetcode-cn.com/problems/move-zeroes/)                                       |       `数组`        | 给定一个数组 `nums`，编写一个函数将所有 `0` 移动到数组的末尾，同时保持非零元素的相对顺序。                                                                           |            [Swift](./Array/283_MoveZeroes.swift)
[27\. 移除元素](https://leetcode-cn.com/problems/remove-element/)                                    |       `数组`        | 给定一个数组 _nums_ 和一个值 _val_，你需要[原地](https://baike.baidu.com/item/原地算法)移除所有数值等于 _val_ 的元素，返回移除后数组的新长度。                            |           [Swift](./Array/27_RemoveElement.swift)
[26\. 删除排序数组中的重复项](https://leetcode-cn.com/problems/remove-duplicates-from-sorted-array/)        |       `数组`        | 给定一个排序数组，你需要在[原地](http://baike.baidu.com/item/原地算法)删除重复出现的元素，使得每个元素只出现一次，返回移除后数组的新长度。                                         |  [Swift](./Array/26_RemoveDuplicatesFromSortedArray.swift)
[75\. 颜色分类](https://leetcode-cn.com/problems/sort-colors/)                                       |  `数组` `排序` `双指针`  | 给定一个包含红色、白色和蓝色，一共 _n_ 个元素的数组，[原地](https://baike.baidu.com/item/原地算法)对它们进行排序，使得相同颜色的元素相邻，并按照红色、白色、蓝色顺序排列。                      |             [Swift](./Array/75_SortColors.swift)
[215\. 数组中的第K个最大元素](https://leetcode-cn.com/problems/kth-largest-element-in-an-array/)           |  `数组` `排序` `多指针`  | 在未排序的数组中找到第 **k** 个最大的元素。请注意，你需要找的是数组排序后的第 k 个最大的元素，而不是第 k 个不同的元素。                                                            |      [Swift](./Array/215_FindKthLargestInAnArray.swift)
[88\. 合并两个有序数组](https://leetcode-cn.com/problems/merge-sorted-array/)                            |    `数组` `双指针`     | 给定两个有序整数数组 _nums1_ 和 _nums2_，将 _nums2_ 合并到 _nums1_ 中_，_使得 _num1_ 成为一个有序数组。                                                    |          [Swift](./Array/88_MergeSortedArray.swift)
[167\. 两数之和 II - 输入有序数组](https://leetcode-cn.com/problems/two-sum-ii-input-array-is-sorted/)     | `数组` `双指针` `二分查找` | 给定一个已按照**_升序排列\_** 的有序数组，找到两个数使得它们相加之和等于目标数。                                                                                  |             [Swift](./Array/167_TwoSumII.swift)
[125\. 验证回文串](https://leetcode-cn.com/problems/valid-palindrome/)                                |    `数组` `指针碰撞`    | 给定一个字符串，验证它是否是回文串，只考虑字母和数字字符，可以忽略字母的大小写。                                                                                      |          [Swift](./Array/125_ValidPalindrome.swift)
[345\. 反转字符串中的元音字母](https://leetcode-cn.com/problems/reverse-vowels-of-a-string/)                |    `数组` `指针碰撞`    | 编写一个函数，以字符串作为输入，反转该字符串中的元音字母。                                                                                                 |      [Swift](./Array/345_ReverseVowelsOfAString.swift)
[11\. 盛最多水的容器](https://leetcode-cn.com/problems/container-with-most-water/)                      |    `数组` `双指针`     | 给定 n 个非负整数 a1，a2，...，an，每个数代表坐标中的一个点 (i, ai) 。在坐标内画 n 条垂直线，垂直线 i 的两个端点分别为 (i, ai) 和 (i, 0)。找出其中的两条线，使得它们与 x 轴共同构成的容器可以容纳最多的水。 |       [Swift](./Array/11_ContainerWithMostWater.swift)
[209\. 长度最小的子数组](https://leetcode-cn.com/problems/minimum-size-subarray-sum/)                    | `数组` `双指针` `二分查找` | 给定一个含有 **n** 个正整数的数组和一个正整数 **s ，**找出该数组中满足其和 **≥ s** 的长度最小的连续子数组**。**如果不存在符合条件的连续子数组，返回 0。                                    |      [Swift](./Array/209_MinimumSizeSubarraySum.swift)
[695. 岛屿的最大面积](https://leetcode-cn.com/problems/max-area-of-island/) | `数组` `深度优先搜索` | 找到给定的二维数组中最大的岛屿面积 | [Swift](./Array/695_MaxAreaofIsland.swift) 
[45. 跳跃游戏 II](https://leetcode-cn.com/problems/jump-game-ii/) | `数组` `贪心算法` | 使用最少的跳跃次数到达数组的最后一个位置 | [Swift](./Array/45_JumpGameII.swift) 
[560. 和为K的子数组](https://leetcode-cn.com/problems/subarray-sum-equals-k/) | `数组` `哈希表` | 给定一个整数数组和一个整数 **k，**你需要找到该数组中和为 **k** 的连续的子数组的个数。 | [Swift](./Array/560_SubarraySumEqualsK.swift) 

### 字符串

标题                                                                                                 |            标签            | 描述                                                |                                  题解
:------------------------------------------------------------------------------------------------- | :----------------------: | ------------------------------------------------- | :------------------------------------------------------------------:
[67\. 二进制求和](https://leetcode-cn.com/problems/add-binary/)                                         |        `字符串` `数学`        | 给定两个二进制字符串，返回他们的和（用二进制表示）。                        |                 [Swift](./String/67_AddBinary.swift)
[3\. 无重复字符的最长子串](https://leetcode-cn.com/problems/longest-substring-without-repeating-characters/) | `哈希表` `双指针` `字符串` `滑动窗口` | 给定一个字符串，请你找出其中不含有重复字符的 **最长子串** 的长度。              | [Swift](./String/3_LongestSubstringWithoutRepeatingCharacters.swift)
[14\. 最长公共前缀](https://leetcode-cn.com/problems/longest-common-prefix/)                             |          `字符串`           | 编写一个函数来查找字符串数组中的最长公共前缀。                           |            [Swift](./String/14_LongestCommonPrefix.swift)
[93\. 复原IP地址](https://leetcode-cn.com/problems/restore-ip-addresses/)                              |          `字符串`           | 给定一个只包含数字的字符串，复原它并返回所有可能的 IP 地址格式。                |            [Swift](./String/93_RestoreIPAddresses.swift)
[71\. 简化路径](https://leetcode-cn.com/problems/simplify-path/)                                       |        `字符串` `栈`         | 以 Unix 风格给出一个文件的**绝对路径**，你需要简化它。或者换句话说，将其转换为规范路径。 |                [Swift](./Stack/71_SimplifyPath.swift)

### 链表

标题                                                                                      |     标签     | 描述                                           |                           题解
:-------------------------------------------------------------------------------------- | :--------: | :------------------------------------------- | :-----------------------------------------------------:
[24.两两交换链表中的节点](https://leetcode-cn.com/problems/swap-nodes-in-pairs/)                  |    `链表`    | 给定一个链表，两两交换其中相邻的节点，并返回交换后的链表。                |     [Swift](LinkedList/024_SwapNodesInPairs.swift)
[707\. 设计链表](https://leetcode-cn.com/problems/design-linked-list/)                      |    `链表`    | 设计链表的实现。您可以选择使用单链表或双链表。                      |     [Swift](LinkedList/707_DesignLinkedList.swift)
[19\. 删除链表的倒数第N个节点](https://leetcode-cn.com/problems/remove-nth-node-from-end-of-list/) | `链表` `双指针` | 给定一个链表，删除链表的倒数第 _n_ 个节点，并且返回链表的头结点。          | [Swift](LinkedList/19_RemoveNthNodeFromEndOfList.swift)
[203\. 移除链表元素](https://leetcode-cn.com/problems/remove-linked-list-elements/)           |    `链表`    | 删除链表中等于给定值 **val** 的所有节点。                    | [Swift](LinkedList/203_RemoveLinkedListElements.swift)
[328\. 奇偶链表](https://leetcode-cn.com/problems/odd-even-linked-list/)                    | `链表` `多指针` | 给定一个单链表，把所有的奇数节点和偶数节点分别排在一起。                 |     [Swift](LinkedList/328_OddEvenLinkedList.swift)
[234\. 回文链表](https://leetcode-cn.com/problems/palindrome-linked-list/)                  | `链表` `双指针` | 判断一个链表是否为回文链表。                               |   [Swift](LinkedList/234_PalindromeLinkedList.swift)
[2\. 两数相加](https://leetcode-cn.com/problems/add-two-numbers/)                           | `链表` `数学`  | 给出两个 **非空** 的链表用来表示两个非负的整数。                  |        [Swift](LinkedList/2_AddTwoNumbers.swift)
[21\. 合并两个有序链表](https://leetcode-cn.com/problems/merge-two-sorted-lists/)               |    `链表`    | 将两个有序链表合并为一个新的有序链表并返回。                       |    [Swift](LinkedList/21_MergeTwoSortedLists.swift)
[61\. 旋转链表](https://leetcode-cn.com/problems/rotate-list/)                              | `链表` `双指针` | 给定一个链表，旋转链表，将链表每个节点向右移动 _k_ 个位置，其中 _k_ 是非负数。 |         [Swift](LinkedList/61_RotateList.swift)
[25. K 个一组翻转链表](https://leetcode-cn.com/problems/reverse-nodes-in-k-group/) | `链表` | 给定一个链表，每 *k* 个节点一组进行翻转，返回翻转后的链表。 | [Swift](LinkedList/25_ReverseNodesink-Group.swift) 

### 栈

标题                                                                                                 |    标签     | 描述                                                          |                                题解
:------------------------------------------------------------------------------------------------- | :-------: | ----------------------------------------------------------- | :--------------------------------------------------------------:
[1003\. 检查替换后的词是否有效](https://leetcode-cn.com/problems/check-if-word-is-valid-after-substitutions/) | `字符串` `栈` | 按给定规则检查替换后的词有效性                                             | [Swift](./Stack/1003_CheckIfWordIsValidAfterSubstitutions.swift)
[71\. 简化路径](https://leetcode-cn.com/problems/simplify-path/)                                       | `字符串` `栈` | 以 Unix 风格给出一个文件的**绝对路径**，你需要简化它。或者换句话说，将其转换为规范路径。           |              [Swift](./Stack/71_SimplifyPath.swift)
[155\. 最小栈](https://leetcode-cn.com/problems/min-stack/)                                           | `栈`、`设计`  | 设计一个支持 push，pop，top 操作，并能在常数时间内检索到最小元素的栈。                   |                [Swift](Stack/155_MinStack.swift)
[20\. 有效的括号](https://leetcode-cn.com/problems/valid-parentheses/)                                  | `字符串` `栈` | 给定一个只包括 `'('`，`')'`，`'{'`，`'}'`，`'['`，`']'` 的字符串，判断字符串是否有效。 |             [Swift](Stack/20_ValidParentheses.swift)
[739\. 每日温度](https://leetcode-cn.com/problems/daily-temperatures/)                                 | `栈` `哈希表` | 根据每日 `气温` 列表，请重新生成一个列表，对应位置的输入是你需要再等待多久温度才会升高超过该日的天数。       |            [Swift](Stack/739_DailyTemperatures.swift)
[150\. 逆波兰表达式求值](https://leetcode-cn.com/problems/evaluate-reverse-polish-notation/)               |    `栈`    | 根据逆波兰表示法，求表达式的值。                                            |      [Swift](Stack/150_EvaluateReversePolishNotation.swift)

### 队列

标题                                                                      | 标签        | 描述       | 题解
----------------------------------------------------------------------- | --------- | -------- | --------------------------------------------
[622\. 设计循环队列](https://leetcode-cn.com/problems/design-circular-queue/) | `设计` `队列` | 设计循环队列实现 | [Swift](Queue/622_DesignCircularQueue.swift)

### 散列表

标题 | 标签 | 描述 | 题解
-- | -- | -- | --
   |    |

### 二叉树

标题 | 标签 | 描述 | 题解
-- | -- | -- | :-:
 [98. 验证二叉搜索树](https://leetcode-cn.com/problems/validate-binary-search-tree) | `树` `深度优先搜索` |给定一个二叉树，判断其是否是一个有效的二叉搜索树。|[Swift](./Tree/98_ValidateBinarySearchTree.swift)
 [236. 二叉树的最近公共祖先](https://leetcode-cn.com/problems/lowest-common-ancestor-of-a-binary-tree/) | `树` `深度优先搜索` |给定一个二叉树, 找到该树中两个指定节点的最近公共祖先。|[Swift](./Tree/236_LowestCommonAncestorofaBinaryTree.swift)
 [102. 二叉树的层序遍历](https://leetcode-cn.com/problems/binary-tree-level-order-traversal/) | `树` `广度优先搜索` |给定一个二叉树，返回其按 **层序遍历** 得到的节点值。 （即逐层地，从左到右访问所有节点）。|[Swift](./Tree/102_BinaryTreeLevelOrderTraversal.swift)

### 堆

标题 | 标签 | 描述 | 题解
-- | -- | -- | --
   |    |

### 跳表

标题 | 标签 | 描述 | 题解
-- | -- | -- | --
   |    |

### 图

标题 | 标签 | 描述 | 题解
-- | -- | -- | --
   |    |

### Trie-树

标题 | 标签 | 描述 | 题解
-- | -- | -- | --
   |    |

## 算法

算法要作用在特定的数据结构之上

- [递归](#递归)
- [排序](#排序)
- [二分查找](#二分查找)
- [搜索](#搜索)
- [哈希算法](#哈希算法)
- [贪心算法](#贪心算法)
- [分治算法](#分治算法)
- [回溯算法](#回溯算法)
- [动态规划](#动态规划)  [`📔`](./DP/README.md)
- [字符串匹配算法](#字符串匹配算法)

### 递归

标题 | 标签 | 描述 | 题解
-- | -- | -- | --
   |    |

### 排序

- [常见排序算法](./Sort/SortingAlgorithms.swift)：冒泡、选择、插入、堆排序、归并排序、快速排序

标题                                                            |    标签     | 描述                                  |                  题解
:------------------------------------------------------------ | :-------: | :---------------------------------- | :-----------------------------------:
274\. [H指数](https://leetcode-cn.com/problems/h-index/)        | `排序` `哈希` | 给定论文被引用次数的数组。编写一个方法，计算出研究者的 _h_ 指数。 |     [Swfit](./274_H-Index.swift)
[912\. 排序数组](https://leetcode-cn.com/problems/sort-an-array/) | `排序` `数组` | 给你一个整数数组 `nums`，请你将该数组升序排列。         | [Swift](./Sort/912_SortAnArray.swift)

### 二分查找

- [二分查找](./BinarySearch/BinarySearch.swift)

标题 | 标签 | 描述 | 题解
-- | -- | -- | --
 [33. 搜索旋转排序数组](https://leetcode-cn.com/problems/search-in-rotated-sorted-array/) | `数组` `二分查找` |按照升序排序的数组在预先未知的某个点上进行了旋转，在该数组中查找目标值。|[Swift](./BinarySearch/33_ SearchinRotatedSortedArray.swift)

### 搜索

标题 | 标签 | 描述 | 题解
-- | -- | -- | --
   |    |

### 哈希算法

标题 | 标签 | 描述 | 题解
-- | -- | -- | --
   |    |

### 贪心算法

标题 | 标签 | 描述 | 题解
-- | -- | -- | --
 [45. 跳跃游戏 II](https://leetcode-cn.com/problems/jump-game-ii/) | `数组` `贪心算法` |使用最少的跳跃次数到达数组的最后一个位置|[Swift](./Array/45_JumpGameII.swift)

### 分治算法

标题 | 标签 | 描述 | 题解
-- | -- | -- | --
   |    |

### 回溯算法

标题 | 标签 | 描述 | 题解
-- | -- | -- | --
   |    |

### 动态规划

标题                                                               |         标签         | 描述                                                    |                   题解
:--------------------------------------------------------------- | :----------------: | :---------------------------------------------------- | :------------------------------------:
[53\. 最大子序和](https://leetcode-cn.com/problems/maximum-subarray/) | `数组` `动态规划` `分治算法` | 给定一个整数数组 `nums` ，找到一个具有最大和的连续子数组（子数组最少包含一个元素），返回其最大和。 | [Swift](./DP/53_MaximumSubarray.swift)
[983. 最低票价](https://leetcode-cn.com/problems/minimum-cost-for-tickets/) | `动态规划` | 给定的列表 `days` 中列出的每一天的旅行所需要的最低消费。 | [Swift](./DP/983_MinimumCostForTickets.swift) 
[221. 最大正方形](https://leetcode-cn.com/problems/maximal-square/) | `动态规划` | 在一个由 0 和 1 组成的二维矩阵内，找到只包含 1 的最大正方形，并返回其面积。 | [Swift](./DP/221_MaximalSquare.swift) 
[152. 乘积最大子数组](https://leetcode-cn.com/problems/maximum-product-subarray/) | `数组` `动态规划` | 给定一个整数数组 `nums` ，找出数组中乘积最大的连续子数组（该子数组中至少包含一个数字），并返回该子数组所对应的乘积。 | [Swift](DP/152_MaximumProductSubarray.swift) 

### 字符串匹配算法

标题                                                                             |     标签     | 描述                          |                    题解
:----------------------------------------------------------------------------- | :--------: | :-------------------------- | :---------------------------------------:
[8.字符串转换整数 (atoi)](https://leetcode-cn.com/problems/string-to-integer-atoi/)   | `数学` `字符串` | 实现一个 `atoi` 函数，使其能将字符串转换成整数 |   [Swift](./008_StringToInteger.swift)
[151\. 翻转字符串里的单词](https://leetcode-cn.com/problems/reverse-words-in-a-string/) |   `字符串`    | 给定一个字符串，逐个翻转字符串中的每个单词。      | [Swift](./151_ReverseWordsInString.swift)
[880\. 索引处的解码字符串](https://leetcode-cn.com/problems/decoded-string-at-index/)   | `字符串`、`余数` | 给定编码字符串，查找解码字符串中的第 K 个字母    | [Swift](./880_DecodedStringAtIndex.swift)
