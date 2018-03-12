# Project Euler
>>>[欧拉计划](https://projecteuler.net/archives)(Project Euler)是一个解题网站，包括一系列有挑战性的数学与计算机编程题；要解开它们，需要的不止是数学知识：尽管数学能够帮助你找到一些优雅而有效的方法，大多数题目仍需要借助计算机和编程技巧来完成解答。本系列会持续按序更新对全部问题的基于Python3的解决方法。此外本项目仅提供问题的中文版以及code，英文题目请参见网站。

### 001. 3和5的倍数(Multiples of 3 and 5)

小于10的非零自然数中是3或者5的倍数有3、5、6、9，这四个数的和为23。计算小于1000的自然数中是3或者5的倍数的所有数的和。

### 002. 斐波那契数列中的偶数(Even Fibonacci numbers)

**斐波那契数列**中每一项均是由前两项的和组成，以1和2作为开始的两项，则前10项为1、2、3、5、8、13、21、34、59、89。请计算最后一项不超过400万的斐波那契数列中的所有偶数之和。

### 003. 最大素因数(Largest prime factor)

13195的素因数为5、17、13和29。求60051475143的最大素因数。

### 004. 最大的回文乘积数(Largest palindrome product)

所谓**回文数**就是从后往前和从前往后读是一样的数。由两个2位数相乘得到的最大回文乘积是 9009 = 91 × 99。找出由两个3位数相乘得到的最大回文乘积数。

### 005. 最小倍数(Smallest multiple)

能被1到10这10个数整除的最小的正数是2520。计算最小的能够被1到20整除的正数。

### 006. 平方的和与和的平方之差(Sum square difference)

前10个自然数平方的和是：1<sup>2</sup> + 2<sup>2</sup>+… + 10<sup>2</sup> = 385。前10个自然数和的平方是：(1 + 2 + … + 10)<sup>2</sup> = 55<sup>2</sup>=3025。因此前10个自然数的平方的和与和的平方之差是 3025−385=2640。求前100个自然数平方的和与和的平方之差

### 007. 第10001个素数(10001st prime)

如果要依次列出前6个素数的话，它们是：2、3、5、7、11和13。可以看出，第6个素数是13。求第10001个素数。

### 008. 连续数字最大乘积(Largest product in a series)

在下面的1000个正整数中，连续4个数字的最大乘积是 9 × 9 × 8 × 9 = 5832。

```
73167176531330624919225119674426574742355349194934
96983520312774506326239578318016984801869478851843
85861560789112949495459501737958331952853208805511
12540698747158523863050715693290963295227443043557
66896648950445244523161731856403098711121722383113
62229893423380308135336276614282806444486645238749
30358907296290491560440772390713810515859307960866
70172427121883998797908792274921901699720888093776
65727333001053367881220235421809751254540594752243
52584907711670556013604839586446706324415722155397
53697817977846174064955149290862569321978468622482
83972241375657056057490261407972968652414535100474
82166370484403199890008895243450658541227588666881
16427171479924442928230863465674813919123162824586
17866458359124566529476545682848912883142607690042
24219022671055626321111109370544217506941658960408
07198403850962455444362981230987879927244284909188
84580156166097919133875499200524063689912560717606
05886116467109405077541002256983155200055935729725
71636269561882670428252483600823257530420752963450
```

找出这个1000个正整数中乘积最大的连续的13个数字，求它们的乘积。

### 009. 特殊的毕达哥拉斯三元组(Special Pythagorean triplet)

**毕达哥拉斯三元组**是三个自然数a < b < c组成的集合，并满足a<sup>2</sup>+ b<sup>2</sup> = c<sup>2</sup>。 例如3<sup>2</sup> + 4<sup>2</sup> = 9 + 16 = 25 = 5<sup>2</sup>。有且只有一个毕达哥拉斯三元组满足 a + b + c = 1000。求这个三元组的乘积abc。

### 010. 素数之和(Summation of primes)

所有小于10的素数的和为2 + 3 + 5 + 7 = 17。求小于两百万的所有素数之和。

### 011. 数字方阵中的最大乘积(Largest product in a grid)

在下面20×20的数字方阵中，以第7行第9列的数字26开始，右下对角线方向的3个数字分别是63,78,14。

```
08 02 22 97 38 15 00 40 00 75 04 05 07 78 52 12 50 77 91 08
49 49 99 40 17 81 18 57 60 87 17 40 98 43 69 48 04 56 62 00
81 49 31 73 55 79 14 29 93 71 40 67 53 88 30 03 49 13 36 65
52 70 95 23 04 60 11 42 69 24 68 56 01 32 56 71 37 02 36 91
22 31 16 71 51 67 63 89 41 92 36 54 22 40 40 28 66 33 13 80
24 47 32 60 99 03 45 02 44 75 33 53 78 36 84 20 35 17 12 50
32 98 81 28 64 23 67 10 26 38 40 67 59 54 70 66 18 38 64 70
67 26 20 68 02 62 12 20 95 63 94 39 63 08 40 91 66 49 94 21
24 55 58 05 66 73 99 26 97 17 78 78 96 83 14 88 34 89 63 72
21 36 23 09 75 00 76 44 20 45 35 14 00 61 33 97 34 31 33 95
78 17 53 28 22 75 31 67 15 94 03 80 04 62 16 14 09 53 56 92
16 39 05 42 96 35 31 47 55 58 88 24 00 17 54 24 36 29 85 57
86 56 00 48 35 71 89 07 05 44 44 37 44 60 21 58 51 54 17 58
19 80 81 68 05 94 47 69 28 73 92 13 86 52 17 77 04 89 55 40
04 52 08 83 97 35 99 16 07 97 57 32 16 26 26 79 33 27 98 66
88 36 68 87 57 62 20 72 03 46 33 67 46 55 12 32 63 93 53 69
04 42 16 73 38 25 39 11 24 94 72 18 08 46 29 32 40 62 76 36
20 69 36 41 72 30 23 88 34 62 99 69 82 67 59 85 74 04 36 16
20 73 35 29 78 31 90 01 74 31 49 71 48 86 81 16 23 57 05 54
01 70 54 71 83 51 54 69 16 92 33 48 61 43 52 01 89 19 67 48
```

这四个数的乘积是26 × 63 × 78 × 14 = 1788696。在这个20×20数字方阵中，计算4个在同一个方向（从下至上、从上至下、从右至左、从左至右或者对角线）上的紧邻的数的最大乘积。

### 012. 可约三角数(Highly divisible triangular number)

三角数数列是通过逐个加上自然数来生成的。例如，第7个三角形数是 1 + 2 + 3 + 4 + 5 + 6 + 7 = 28。三角形数数列的前十项分别是：1, 3, 6, 10, 15, 21, 28, 36, 45, 55, … 下面是前七个三角数的所有约数：
&emsp;&emsp;__1: 1__
&emsp;&emsp;__3: 1、3__
&emsp;&emsp;__6: 1、2、3、6__
&emsp;&emsp;__10: 1、2、5、10__
&emsp;&emsp;__15: 1、3、5、15__
&emsp;&emsp;__21: 1、3、7、21__
&emsp;&emsp;__28: 1、2、4、7、14、28__

可以看出，28是第一个拥有超过5个约数的三角数。求第一个拥有超过500个约数的三角数。

### 013. 大数之和(Large sum)

计算出以下一百个50位数的和的前十位数字


### 014. 最长的考拉兹序列(Longest Collatz sequence)

所谓**回文数**就是从后往前和从前往后读是一样的数。由两个2位数相乘得到的最大回文乘积是 9009 = 91 × 99。找出由两个3位数相乘得到的最大回文乘积数。

### 015. 网格路径(Lattice paths)

能被1到10这10个数整除的最小的正数是2520。计算最小的能够被1到20整除的正数。

### 016. 平方的和与和的平方之差(Sum square difference)

前10个自然数平方的和是：1<sup>2</sup> + 2<sup>2</sup>+… + 10<sup>2</sup> = 385。前10个自然数和的平方是：(1 + 2 + … + 10)<sup>2</sup> = 55<sup>2</sup>=3025。因此前10个自然数的平方的和与和的平方之差是 3025−385=2640。求前100个自然数平方的和与和的平方之差

### 017. 第10001个素数(10001st prime)

如果要依次列出前6个素数的话，它们是：2、3、5、7、11和13。可以看出，第6个素数是13。求第10001个素数。










