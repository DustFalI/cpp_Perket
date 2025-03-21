# cpp_PERKET
C++练习 PERKET

PERKET

题目描述：
Perket 是一种流行的美食。为了做好 Perket，厨师必须谨慎选择食材，以在保持传统风味的同时尽可能获得最全面的味道。你有 $n$ 种可支配的配料。对于每一种配料，我们知道它们各自的酸度 $s$ 和苦度 $b$。当我们添加配料时，总的酸度为每一种配料的酸度总乘积；总的苦度为每一种配料的苦度的总和。
众所周知，美食应该做到口感适中，所以我们希望选取配料，以使得酸度和苦度的绝对差最小。
另外，我们必须添加至少一种配料，因为没有任何食物以水为配料的。

输入格式：
第一行一个整数 $n$，表示可供选用的食材种类数。
接下来 $n$ 行，每行 $2$ 个整数 $s_i$ 和 $b_i$，表示第 $i$ 种食材的酸度和苦度。

输出格式：
一行一个整数，表示可能的总酸度和总苦度的最小绝对差。

思路：
针对每一种配料，遍历所有搭配的可能性。
最后三行代码是关键，通过二叉树理解会更容易，用例子：配料1234，从一开始，加加加，如何归，加加减，归，加减减，；归减减减。
本题递归的思路和考前抱佛脚类似。
一定要用二叉树来理解。
