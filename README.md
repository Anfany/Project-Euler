# Project Euler
>>>[欧拉计划](https://projecteuler.net/archives)(Project Euler)是一个解题网站，包括一系列有挑战性的数学与计算机编程题；要解开它们，需要的不止是数学知识：尽管数学能够帮助你找到一些优雅而有效的方法，大多数题目仍需要借助计算机和编程技巧来完成解答。本系列会持续按序更新对全部问题的基于Python3的解决方法。此外本项目仅提供问题的中文版以及code，英文题目请参见网站。

### 001. 3和5的倍数(Multiples of 3 and 5)

小于10的非零自然数中是3或者5的倍数有3、5、6、9，这四个数的和为23。

计算小于1000的自然数中是3或者5的倍数的所有数的和。

### 002. 斐波那契数列中的偶数(Even Fibonacci numbers)

**斐波那契数列**中每一项均是由前两项的和组成，以1和2作为开始的两项，则前10项为1、2、3、5、8、13、21、34、59、89。

请计算最后一项不超过400万的斐波那契数列中的所有偶数之和。

### 003. 最大素因数(Largest prime factor)

13195的素因数为5、17、13和29。

求60051475143的最大素因数。

### 004. 最大的回文乘积数(Largest palindrome product)

所谓**回文数**就是从后往前和从前往后读是一样的数。由两个2位数相乘得到的最大回文乘积是 9009 = 91 × 99。

找出由两个3位数相乘得到的最大回文乘积数。

### 005. 最小倍数(Smallest multiple)

能被1到10这10个数整除的最小的正数是2520。

计算最小的能够被1到20整除的正数。

### 006. 平方的和与和的平方之差(Sum square difference)

前10个自然数平方的和是：1<sup>2</sup> + 2<sup>2</sup>+… + 10<sup>2</sup> = 385。前10个自然数和的平方是：(1 + 2 + … + 10)<sup>2</sup> = 55<sup>2</sup>=3025。因此前10个自然数的平方的和与和的平方之差是 3025−385=2640。

求前100个自然数平方的和与和的平方之差。

### 007. 第10001个素数(10001st prime)

如果要依次列出前6个素数的话，它们是：2、3、5、7、11和13。可以看出，第6个素数是13。

求第10001个素数。

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

**毕达哥拉斯三元组**是三个自然数a < b < c组成的集合，并满足a<sup>2</sup>+ b<sup>2</sup> = c<sup>2</sup>。 例如3<sup>2</sup> + 4<sup>2</sup> = 9 + 16 = 25 = 5<sup>2</sup>。

有且只有一个毕达哥拉斯三元组满足 a + b + c = 1000。求这个三元组的乘积abc。

### 010. 素数之和(Summation of primes)

所有小于10的素数的和为2 + 3 + 5 + 7 = 17。

求小于两百万的所有素数之和。

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

__1: 1__

__3: 1、3__

__6: 1、2、3、6__

__10: 1、2、5、10__

__15: 1、3、5、15__

__21: 1、3、7、21__

__28: 1、2、4、7、14、28__

可以看出，28是第一个拥有超过5个约数的三角数。求第一个拥有超过500个约数的三角数。

### 013. 大数之和(Large sum)

计算出以下一百个50位数的和的前十位数字

```
37107287533902102798797998220837590246510135740250
46376937677490009712648124896970078050417018260538
74324986199524741059474233309513058123726617309629
91942213363574161572522430563301811072406154908250
23067588207539346171171980310421047513778063246676
89261670696623633820136378418383684178734361726757
28112879812849979408065481931592621691275889832738
44274228917432520321923589422876796487670272189318
47451445736001306439091167216856844588711603153276
70386486105843025439939619828917593665686757934951
62176457141856560629502157223196586755079324193331
64906352462741904929101432445813822663347944758178
92575867718337217661963751590579239728245598838407
58203565325359399008402633568948830189458628227828
80181199384826282014278194139940567587151170094390
35398664372827112653829987240784473053190104293586
86515506006295864861532075273371959191420517255829
71693888707715466499115593487603532921714970056938
54370070576826684624621495650076471787294438377604
53282654108756828443191190634694037855217779295145
36123272525000296071075082563815656710885258350721
45876576172410976447339110607218265236877223636045
17423706905851860660448207621209813287860733969412
81142660418086830619328460811191061556940512689692
51934325451728388641918047049293215058642563049483
62467221648435076201727918039944693004732956340691
15732444386908125794514089057706229429197107928209
55037687525678773091862540744969844508330393682126
18336384825330154686196124348767681297534375946515
80386287592878490201521685554828717201219257766954
78182833757993103614740356856449095527097864797581
16726320100436897842553539920931837441497806860984
48403098129077791799088218795327364475675590848030
87086987551392711854517078544161852424320693150332
59959406895756536782107074926966537676326235447210
69793950679652694742597709739166693763042633987085
41052684708299085211399427365734116182760315001271
65378607361501080857009149939512557028198746004375
35829035317434717326932123578154982629742552737307
94953759765105305946966067683156574377167401875275
88902802571733229619176668713819931811048770190271
25267680276078003013678680992525463401061632866526
36270218540497705585629946580636237993140746255962
24074486908231174977792365466257246923322810917141
91430288197103288597806669760892938638285025333403
34413065578016127815921815005561868836468420090470
23053081172816430487623791969842487255036638784583
11487696932154902810424020138335124462181441773470
63783299490636259666498587618221225225512486764533
67720186971698544312419572409913959008952310058822
95548255300263520781532296796249481641953868218774
76085327132285723110424803456124867697064507995236
37774242535411291684276865538926205024910326572967
23701913275725675285653248258265463092207058596522
29798860272258331913126375147341994889534765745501
18495701454879288984856827726077713721403798879715
38298203783031473527721580348144513491373226651381
34829543829199918180278916522431027392251122869539
40957953066405232632538044100059654939159879593635
29746152185502371307642255121183693803580388584903
41698116222072977186158236678424689157993532961922
62467957194401269043877107275048102390895523597457
23189706772547915061505504953922979530901129967519
86188088225875314529584099251203829009407770775672
11306739708304724483816533873502340845647058077308
82959174767140363198008187129011875491310547126581
97623331044818386269515456334926366572897563400500
42846280183517070527831839425882145521227251250327
55121603546981200581762165212827652751691296897789
32238195734329339946437501907836945765883352399886
75506164965184775180738168837861091527357929701337
62177842752192623401942399639168044983993173312731
32924185707147349566916674687634660915035914677504
99518671430235219628894890102423325116913619626622
73267460800591547471830798392868535206946944540724
76841822524674417161514036427982273348055556214818
97142617910342598647204516893989422179826088076852
87783646182799346313767754307809363333018982642090
10848802521674670883215120185883543223812876952786
71329612474782464538636993009049310363619763878039
62184073572399794223406235393808339651327408011116
66627891981488087797941876876144230030984490851411
60661826293682836764744779239180335110989069790714
85786944089552990653640447425576083659976645795096
66024396409905389607120198219976047599490197230297
64913982680032973156037120041377903785566085089252
16730939319872750275468906903707539413042652315011
94809377245048795150954100921645863754710598436791
78639167021187492431995700641917969777599028300699
15368713711936614952811305876380278410754449733078
40789923115535562561142322423255033685442488917353
44889911501440648020369068063960672322193204149535
41503128880339536053299340368006977710650566631954
81234880673210146739058568557934581403627822703280
82616570773948327592232845941706525094512325230608
22918802058777319719839450180888072429661980811197
77158542502016545090413245809786882778948721859617
72107838435069186155435662884062257473692284509516
20849603980134001723930671666823555245252804609722
53503534226472524250874054075591789781264330331690
```

### 014. 最长的考拉兹序列(Longest Collatz sequence)

在正整数集上定义如下的迭代序列：

__n ----> n/2 （若n为偶数）__   

__n ----> 3n + 1 （若n为奇数）__

从13开始应用上述规则，我们可以生成如下的序列：13 → 40 → 20 → 10 → 5 → 16 → 8 → 4 → 2 → 1。可以看出这个序列（从13开始到1结束）共有10项。

虽然还没有被证明，但普遍认为，从任何数开始最终都能迭代至1（这就是“考拉兹猜想”）。计算从小于一百万的哪个数开始，生成的序列最长。

**注**：序列开始生成后允许其中的项超过一百万。

### 015. 网格路径(Lattice paths)

从一个2×2方阵的左上角出发，只允许向右或向下移动，则恰好有6条通往右下角的路径。

![image](https://projecteuler.net/project/images/p015.gif)

对于20×20方阵来说，这样的路径有几条。

### 016. 幂的数字和(Power digit sum)

2<sup>15</sup>=32768，32768的各位数字之和为 3 + 2 + 7 + 6 + 8 = 26。

计算2<sup>1000</sup>的各位数字之和。

### 017. 英文字母个数(Number letter counts)

把1到5写成英文单词，分别是：one, two, three, four, five，这些单词一共用了3 + 3 + 5 + 4 + 4 = 19个字母。

把1到1000都写成英文单词，共用多少字母。

**注**： 不要算上空格和连字符。例如，342（three hundred and forty-two）包含23个字母，而115（one hundred and fifteen）包含20个字母。单词“and”的使用方式遵循英式英语的规则。

### 018. 最大路径和(基础版)(Maximum path sum I)

从下图三角形的顶端出发，不断移动到在下一行与其相邻的元素(例如数字7只能移动到下一行的2或者4，而不能到达6)，得到的最大路径和是23。

```
   3
  7 4
 2 4 6
8 5 9 3
```

如上图，最大路径和为 3 + 7 + 4 + 9 = 23。求从下面的三角形顶端出发到达底部，所能够得到的最大路径和。

```
                         75
                        95 64
                      17 47 82
                    18 35 87 10
                  20 04 82 47 65
                19 01 23 75 03 34
               88 02 77 73 07 63 67
             99 65 04 28 06 16 70 92
           41 41 26 56 83 40 80 70 33
         41 48 72 33 47 32 37 16 94 29
       53 71 44 65 25 43 91 52 97 51 14
     70 11 33 28 77 73 17 78 39 68 17 57
    91 71 52 38 17 14 91 43 58 50 27 29 48
  63 66 04 68 89 53 67 30 73 16 69 87 40 31
04 62 98 27 23 09 70 98 73 93 38 53 60 04 23
```

**注**：在上面这个问题中，由于只有16384条路径，通过尝试所有的路径来解决问题是可行的。但是如果三角形变大，暴力破解将不能解决，而需要一个更加聪明的办法。

### 019. 星期日个数(Counting Sundays)

1900年1月1日是星期一；天数是30天的月份有四、六、九、十一，剩下的月份除了二月，其他都是31天；闰年的二月有29天，平年的二月是28天；闰年指的是能够被4整除却不能被100整除的年份，或者能够被400整除的年份。

在二十世纪（1901年1月1日到2000年12月31日）中，有多少个月的1号是星期日。

### 020. 阶乘的数字之和(Factorial digit sum)

n! 表示的是 n × (n − 1) × … × 3 × 2 × 1。例如：10! = 10 × 9 × … × 3 × 2 × 1 = 3628800，所以10的阶乘的数字之和是 3 + 6 + 2 + 8 + 8 + 0 + 0 = 27。

求出100!的各位数字和。

### 021. 亲和数(Amicable numbers)

记d(n)为n的所有真因数（小于n且整除n的正整数）之和。如果d(a) = b且d(b) = a，且a ≠ b，那么a和b构成一个亲和数对，a和b被称为亲和数。例如，220的真因数包括1、2、4、5、10、11、20、22、44、55和110，因此d(220) = 284。284的真因数包括1、2、4、71和142，因此d(284) = 220。说明284和220是亲和数。

求所有小于10000的亲和数的和。

### 022. 姓名之分(Names scores)

文本[names.txt](https://projecteuler.net/project/resources/p022_names.txt)中包含了五千多个姓名，首先将姓名按字母顺序排列，然后算出每个姓名字母的和值，最后乘以该姓名排列后的位置，以计算出__姓名之分__。例如，按照字母顺序排列后，姓名COLIN的位置是938，其字母的和值是3 + 15 + 12 + 9 + 14 = 53。因此COLIN的姓名之分是938 × 53 = 49714。

计算文件中所有姓名的姓名之分的和。

### 023. 非盈数之和的和(Non-abundant sums)

完全数是指真因数之和等于自身的那些数。例如，28的真因数之和为1 + 2 + 4 + 7 + 14 = 28，因此28是一个完全数。一个数n被称为亏数，如果它的真因数之和小于n；反之则被称为**盈数**。由于12是最小的盈数，它的真因数之和为1 + 2 + 3 + 4 + 6 = 16，所以最小的能够表示成两个盈数之和的数是24。

通过数学分析可以得出，所有大于28123的数都可以被写成两个盈数的和；因此28123是不能被分成两个盈数的和的最大的数的上界。

找出所有不能被写成两个盈数之和的正整数的和。

### 024. 字典序排列(Lexicographic permutations)

**排列**指的是将一组物体进行有顺序的放置。例如，3124是数字1、2、3、4的一个排列。如果把所有排列按照数字大小或字母先后进行排序，我们称之为字典序排列。0、1、2的字典序排列是：

**012，021，102，120，201，210**

数字0、1、2、3、4、5、6、7、8、9的字典序排列中第一百万位的排列是。

### 025. 1000位的斐波那契数(1000-digit Fibonacci number)

斐波那契数列是按如下递归关系定义的数列：

**F1 = 1**　

**F2 = 1**

**Fn = Fn−1 + Fn−2**

因此斐波那契数列的前12项分别是：

**F1 = 1， F2 = 1，　F3 = 2**　

**F4 = 3，　F5 = 5，　F6 = 8**　

**F7 = 13，　F8 = 21，　F9 = 34**

**F10 = 55，　F11 = 89，　F12 = 144**　　

不难看出，第一个有3位数字的是第12项F12。在斐波那契数列中，第一个有1000位数字的是第几项。

### 026. 最长的倒数循环节(Reciprocal cycles)

单位分数是指分子为1的分数。分母从2到10的单位分数的十进制表示如下所示：

__1/2= 0.5__，
__1/3= 0.(3)__，
__1/4= 0.25__

__1/5= 0.2__，
__1/6= 0.1(6)__，
__1/7= 0.(142857)__

__1/8= 0.125__，
__1/9= 0.(1)__，
__1/10= 0.1__

这里0.1(6)表示0.166666…，括号内表示有一位的循环节。可知，1/7有六位循环节。

找出小于1000的正整数d，其倒数的十进制表示的小数部分有最长的循环节。

### 027. 二次“素数生成”多项式(Quadratic primes)

欧拉发现了这个著名的二次多项式： __n<sup>2</sup> + n + 41__ 。n从0到39，这个二次多项式生成了40个素数。然而，当n = 40时，40<sup>2</sup> + 40 + 41 = 40(40 + 1) + 41能够被41整除，同时显然当n = 41时，41<sup>2</sup> + 41 + 41也能被41整除。

随后，另一个神奇的多项式 __n<sup>2</sup> − 79n + 1601__ 被发现了，对于n从0到79，它生成了80个素数。这个多项式的系数-79和1601的乘积为-126479。

考虑以下形式的二次多项式： __n<sup>2</sup> + an + b__ , 满足|a| < 1000且|b| < 1000。其中|n|表示n的绝对值，例如|11| = 11以及|−4| = 4。这其中存在某个二次多项式能够对从0开始尽可能多的连续整数n都生成素数，求其系数a和b的乘积。

### 028. 螺旋数阵对角线(Number spiral diagonals)

从1开始，按顺时针顺序向右铺开的5 × 5螺旋数阵如下所示：

![problem28.png](http://upload-images.jianshu.io/upload_images/4734220-c5162e3e4a4f99d1.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

可以验证，该数阵对角线上的数[红色数字]之和是101。

以同样方式构成的1001 × 1001螺旋数阵对角线上的数之和是。

### 029. 不同的幂(Distinct powers)

考虑所有满足2 ≤ a ≤ 5和2 ≤ b ≤ 5的整数组合生成的幂**a<sup>b</sup>** ：

__2<sup>2</sup>=4, 　2<sup>3</sup>=8, 　2<sup>4</sup>=16, 　2<sup>5</sup>=32__

__3<sup>2</sup>=9, 　3<sup>3</sup>=27, 　3<sup>4</sup>=81, 　3<sup>5</sup>=243__

__4<sup>2</sup>=16, 　4<sup>3</sup>=64, 　4<sup>4</sup>=256, 　4<sup>5</sup>=1024__

__5<sup>2</sup>=25,　 5<sup>3</sup>=125, 　5<sup>4</sup>=625, 　5<sup>5</sup>=3125__

如果把这些幂按照大小排列并去重，我们得到以下由15个不同的项组成的序列：

4, 8, 9, 16, 25, 27, 32, 64, 81, 125, 243, 256, 625, 1024, 3125

在所有满足2 ≤ a ≤ 100和2 ≤ b ≤ 100的整数生成的幂**a<sup>b</sup>** 排列并去重所得到的序列中，有多少项。

### 030. 数字的五次幂(Digit fifth powers)

令人惊讶的是，只有三个数可以写成它们各位数字的四次幂之和：

__1634 = 1<sup>4</sup> + 6<sup>4</sup> + 3<sup>4</sup> + 4<sup>4</sup>__

__8208 = 8<sup>4</sup> + 2<sup>4</sup> + 0<sup>4</sup> + 8<sup>4</sup>__

__9474 = 9<sup>4</sup> + 4<sup>4</sup> + 7<sup>4</sup> + 4<sup>4</sup>__

由于1 = 1<sup>4</sup>不是一个和的形式，因此这里没列出。这些数的和是1634 + 8208 + 9474 = 19316。

找出所有可以写成它们各位数字的五次幂之和的数，并求这些数的和。

### 031. 硬币组合(Coin sums)

英国的货币单位包括英镑£和便士p，在流通中的硬币一共有八种：

**1p, 2p, 5p, 10p, 20p, 50p, £1 (100p), £2 (200p)**
    
以下是组成£2的其中一种方式：

**1×£1 + 1×50p + 2×20p + 1×5p + 1×2p + 3×1p**
    
不限定使用的硬币数目，组成£2有多少种不同的方式。

### 032. 全数字乘积式的和(Pandigital products)
如果一个n位数包含了1至n的所有数字恰好一次，我们称它为**全数字的**；例如，五位数15234就是1至5全数字的。7254是一个特殊的乘积，因为在等式39 × 186 = 7254中，被乘数、乘数和乘积恰好是1至9全数字的。

找出所有被乘数、乘数和乘积恰好是1至9全数字的乘法等式，并求出这些等式中乘积的和。

**注**:有些乘积可能从多个乘法等式中得到，但在求和的时候只计算一次。

### 033. 分数化简(Digit cancelling fractions)

49/98是一个有趣的分数，因为缺乏数学知识的人可能会误认为，等式49/98 = 4/8之所以成立，是因为在分数线上下同时抹除了9的缘故。如果按照这么理解，则存在诸如30/50 = 3/5这样的**平凡解**。

这类有趣的分数恰好有四个非平凡的例子，它们的分数值小于1，且分子和分母都是两位数。将这四个分数的乘积写成最简分数，求此时分母的值。

### 034. 数字阶乘(Digit factorials)

145是个有趣的数，因为有如下关系：

**1! + 4! + 5! = 1 + 24 + 120 = 145**

找出所有各位数字的阶乘和等于其本身的数，并求它们的和。

**注**：1! = 1和2! = 2，由于不是和的形式，所以它们并不在此范围内。

### 035. 循环素数(Circular primes)

197被称为循环素数，因为将它逐位旋转所得到的数：197、971和719都是素数。

小于100的循环素数有十三个：

**2、3、5、7、11、13、17、31、37、71、73、79、97**

小于一百万的循环素数有多少个。

### 036. 二进制回文数(Double-base palindromes)
十进制数585 的二进制表示为1001001001，可以看出它在这两种进制下都是回文数。

找出所有小于一百万，且在十进制和二进制下均是回文数的数，并求它们的和。

**注**：无论在哪种进制下，第一位数均不为0。

### 037. 双向可截短素数(Truncatable primes)

3797有着奇特的性质，不仅它本身是一个素数，而且如果从左往右逐一截去一个数字，剩下的数仍然都是素数：3797、797、97和7；同样地，如果从右往左逐一截去数字，剩下的也依然都是素数：3797、379、37和3。

只有11个数满足上述的性质，求这些数的和。

**注**：2、3、5和7不被视为双向可截短素数。

### 038. 全数字的连接乘积数(Pandigital multiples)
将192分别与1、2、3相乘：

**192 × 1 = 192**

**192 × 2 = 384**

**192 × 3 = 576**

连接这些乘积，我们得到一个1至9全数字的数192384576。我们称192384576为192和(1,2,3)的**连接乘积数**。同样地，将9分别与1、2、3、4、5相乘，得到1至9全数字的数918273645，即是9和(1,2,3,4,5)的连接乘积数。

对于n > 1，所有某个整数和(1,2, … ,n)的连接乘积所构成的数中，最大的1至9全数字的数是。

### 039. 整数边长直角三角形(Integer right triangles)

若三边长{a,b,c}均为整数的直角三角形周长为p，当p = 120时，恰好存在三个不同的解：

**{20,48,52}**

**{24,45,51}**

**{30,40,50}**

在所有的p ≤ 1000中，p取何值时有解的数目最多。

### 040. Champernowne数(Champernowne's constant)

将所有正整数连接起来构造一个十进制无理数如下所示：

**0.123456789101112131415161718192021…**

可以看出小数点后第12位数字是1。

如果dn表示上述无理数小数点后的第n位数字，求下式的值

**d1 × d10 × d100 × d1000 × d10000 × d100000 × d1000000**

### 041. 全数字的素数(Pandigital prime)

如果一个n位数恰好使用了1至n每个数字各一次，我们就称其为**全数字的**。例如，2143就是一个4位全数字数，同时它恰好也是一个素数。

最大的全数字的素数是多少。

### 042. 三角形单词(Coded triangle numbers)

三角形数序列的第n项tn可由公式n(n+1)/2得到；因此前十个三角形数是：

**1, 3, 6, 10, 15, 21, 28, 36, 45, 55, …**

将一个单词中的每个字母分别转化为其在字母表中的顺序并相加，我们可以计算出一个单词的值。例如，单词SKY的值就是 19 + 11 + 25 = 55 = t10。如果一个单词的值是一个三角形数，我们就称这个单词为**三角形单词**。

在文件[words.txt](https://projecteuler.net/project/resources/p042_words.txt)中包含有将近两千个常用英文单词，这其中有多少个三角形单词。


### 043. 子串可整除(Sub-string divisibility)

1406357289是一个0至9的全数字数，因为它由0到9这十个数字排列而成；但除此之外，它还有一个有趣的性质：**子串可整除**

记d1是它的第一个数字，d2是第二个数字，依此类推，我们注意到：

**d2d3d4=406能被2整除**

**d3d4d5=063能被3整除**

**d4d5d6=635能被5整除**

**d5d6d7=357能被7整除**
    
**d6d7d8=572能被11整除**
    
**d7d8d9=728能被13整除**
    
**d8d9d10=289能被17整除**
    
找出所有满足同样性质的0至9全数字数，并求它们的和。

### 044. 五边形数(Pentagon numbers)

五边形数是由公式Pn=n(3n−1)/2生成。前10个五边形数是：

**1, 5, 12, 22, 35, 51, 70, 92, 117, 145, …**
    
可以看出P4 + P7 = 22 + 70 = 92 = P8。然而，它们的差70 − 22 = 48并不是五边形数。

在所有和差均为五边形数的五边形数对Pj和Pk中，找出使D = |Pk − Pj|最小的一对，此时D的值是。

### 045. 三角形数. 五边形数和六角形数(Triangular, pentagonal, and hexagonal)

三角形数、五边形数和六角形数分别由以下公式给出：

**三角形数  Tn=n(n+1)/2 1, 3, 6, 10, 15, …**

**五边形数  Pn=n(3n−1)/2    1, 5, 12, 22, 35, …**

**六边形数  Hn=n(2n−1)  1, 6, 15, 28, 45, …**

可以验证，T285 = P165 = H143 = 40755。

找出下一个同时是三角形数、五边形数和六角形数的数。

### 046. 哥德巴赫的另一个猜想(Goldbach's other conjecture)

哥德巴赫曾猜想：**每个奇合数可以写成一个素数和一个平方的两倍之和**

**9 = 7 + 2×1<sup>2</sup>**
    
**15 = 7 + 2×2<sup>2</sup>**

**21 = 3 + 2×3<sup>2</sup>**

**25 = 7 + 2×3<sup>2</sup>**

**27 = 19 + 2×2<sup>2</sup>**

**33 = 31 + 2×1<sup>2</sup>**

最终这个猜想被推翻了。

最小的不能写成一个素数和一个平方的两倍之和的奇合数是。

### 047. 不同的质因数(Distinct primes factors)

首次出现连续两个数均有两个不同的质因数是：

**14 = 2 × 7**

**15 = 3 × 5**

首次出现连续三个数均有三个不同的质因数是：

**644 = 22 × 7 × 23**

**645 = 3 × 5 × 43**

**646 = 2 × 17 × 19**

首次出现连续四个数均有四个不同的质因数时，其中的第一个数是。

### 048. 自幂方数(Self powers)

前10项的自幂方数的和为

**1<sup>1</sup> + 2<sup>2</sup> + 3<sup>3</sup> + … + 10<sup>10</sup> = 10405071317**

求前1000项的自幂方数的和的最后10位数字。
  
### 049. 重排素数(Prime permutations)

公差为3330的等差序列1487、4817、8147。在两个方面非常特别：

**1，每一项都是素数；**

**2，两两都是数字重新排列的关系。**
    
一位素数、两位素数和三位素数都无法构成满足这些性质的数列，但存在另一个由四位素数构成的递增序列也满足这些性质。将这个数列的三项连接起来得到的12位数是。

### 050. 连续素数的和(Consecutive prime sum)

素数41可以写成六个连续素数的和：

**41 = 2 + 3 + 5 + 7 + 11 + 13**

在小于100的素数中，41能够被写成最多的连续素数的和。在小于1000的素数中，953能够被写成最多的连续素数的和，共包含连续21个素数。

在小于100万的素数中，哪个素数能够被写成最多的连续素数的和。

### 051. 素数数字替换(Prime digit replacements)

将两位数a3的第一个数字替换为任意数字，在九个可能值中有六个是素数：

**13、23、43、53、73、83**

将五位数56aa3的第三和第四位数字替换为相同的任意数字，十个可能值中有七个是素数，这7个素数是：

**56003、56113、56333、56443、56663、56773、56993**
    
56003作为最小的数，也是最小的满足这个性质的素数。

通过将部分数字(不一定相邻)替换为相同的任意数字，有时能够得到八个素数，求满足这一性质的最小素数。

### 052. 倍数重排(Permuted multiples)

125874和它的两倍251748拥有同样的数字，只是排列顺序不同。

有些正整数x满足2x、3x、4x、5x和6x都拥有相同的数字，求其中最小的正整数。

### 053. 组合数(Combinatoric selections)

从五个数1,2,3,4,5中选择三个恰好有十种方式，分别是：

**123、124、125、134、135、145、234、235、245、345**
    
在组合数学中，我们记作：C(5，3)= 10。一般来说，C(n,r)=n!/r!(n−r)!，其中r ≤ n，n! = n×(n−1)×…×3×2×1，且0! = 1。直到n = 23时，才出现了超出一百万的组合数：C(23,10) =1144066。

若数值相等形式不同也视为不同，对于1 ≤ n ≤ 100，有多少个组合数C(n,r)超过一百万。

### 056 幂的数字和(Powerful digit sum)

一**古戈尔**( 10<sup>100</sup> )是一个巨大的数字：1后面跟着100个0。100<sup>100</sup>则更是无法想像地巨大：1后面跟着200个0。尽管这两个数如此巨大，各位的数字和却都只有1。

若a, b < 100，所有a<sup>b</sup>中，具有最大的数字和的数是。
  
### 057 平方根逼近(Square root convergents)

2的平方根可以用一个无限连分数表示：

**√ 2 = 1 + 1/(2 + 1/(2 + 1/(2 + … ))) = 1.414213…**

将连分数计算取前四次迭代展开式分别是：

**1 + 1/2 = 3/2 = 1.5**

**1 + 1/(2 + 1/2) = 7/5 = 1.4**

**1 + 1/(2 + 1/(2 + 1/2)) = 17/12 = 1.41666…**

**1 + 1/(2 + 1/(2 + 1/(2 + 1/2))) = 41/29 = 1.41379…**

接下来的三个迭代展开式分别是**99/70、239/169**和**577/408**，但是直到第八个迭代展开式**1393/985**，分子的位数第一次超过分母的位数。

在前一千个迭代展开式中，有多少个分数分子的位数多于分母的位数。

### 058 螺旋素数(Spiral primes)

从1开始逆时针螺旋着摆放自然数，构造出一个边长为7的螺旋数阵(如下所示)。

**37 36 35 34 33 32 31**

**38 17 16 15 14 13 30**

**39 18 5  4  3  12 29**

**40 19 6  1  2  11 28**

**41 20 7  8  9  10 27**

**42 21 22 23 24 25 26**

**43 44 45 46 47 48 49**

可以发现，所有的奇数平方都在这个螺旋方针的右下对角线上，更有趣的是，在所有对角线上一共有8个素数(加粗的数)，比例达到8/13 ≈ 62%。

在这个方阵外面完整地再加上一层，就能构造出一个边长为9的螺旋方阵。如果不断重复这个过程，当对角线上素数的比例第一次低于10%时，螺旋数阵的边长是。

### 059 异或解密(XOR decryption)

计算机上的每个字符都被指定了一个独特的代码，其中被广泛使用的一种是ASCII码(美国信息交换标准代码)。例如: 大写字母A = 65，星号（*） = 42，小写字母k = 107。

一种现代加密方法是将一个文本文档中的符号先转化为ASCII码，然后将每个字节异或一个根据密钥确定的值。使用异或进行加密的好处在于，只需对密文使用相同的密钥再加密一次就能得到明文，例如，65 XOR 42 = 107，而107 XOR 42 = 65。

为了使加密难以破解，密钥要和明文一样长，由随机的字节构成。用户会把加密过的信息和密钥放置在不同的地方，解密时二者缺一不可。不幸的是，这种方法对大多数人来说并不实用，因此一个略有改进的方法是使用一个密码作为密钥。密码的长度很有可能比信息要短，这时候就循环重复使用这个密码进行加密。这种方法需要达到一种平衡，一方面密码要足够长才能保证安全，另一方面需要充分短以方便记忆。

你的破解任务要简单得多，因为密钥只由三个小写字母构成。在文本[cipher.txt](https://projecteuler.net/project/resources/p059_cipher.txt)中包含了加密后的ASCII码，并且已知明文包含的一定是常见的英文单词，解密这条消息并求出原文的ASCII码之和。

### 060 特殊素数组(Prime pair sets)

3、7、109和673是特别的一组素数。任取其中的两个并且以任意顺序连接起来，其结果仍然是个素数。例如:：选择7和109，任意连接得到的7109和1097均为素数。这组素数的和是792，这是满足这个性质的一组四个素数的最小和。

若有一组包含五个素数，任取其中的两个并且以任意顺序连接起来，其结果仍是个素数，求这样一组素数的最小和。

### 061. 循环多边形数(Cyclical figurate numbers)

三角形数、正方形数、五边形数、六边形数、七边形数和八边形数统称为多边形数。它们分别由如下的公式给出：

**三角形数  P3(n)=n(n+1)/2---->1, 3, 6, 10, 15, …**
**正方形数  P4(n)=n<sup>2</sup>---->1, 4, 9, 16, 25, …**
**五边形数  P5(n)=n(3n−1)/2---->1, 5, 12, 22, 35, …**
**六边形数  P6(n)=n(2n−1)---->1, 6, 15, 28, 45, …**
**七边形数  P7(n)=n(5n−3)/2---->1, 7, 18, 34, 55, …**
**八边形数  P8(n)=n(3n−2)---->1, 8, 21, 40, 65, …**

由三个4位数**8128、2882、8281**构成的有序集有如下三个有趣的性质：

  1. 这个集合是循环的，每个数的后两位是后一个数的前两位(最后一个数的后两位也是第一个数的前两位)；
  2. 每种多边形数——三角形数（P3(127)=8128）、正方形数（P4(91)=8281）和五边形数（P5(44)=2882）——在其中各有一个代表;
  3. 这是唯一一个满足上述性质的4位数有序集；
  
存在唯一一个包含六个4位数的有序循环集，每种多边形数——三角形数、正方形数、五边形数、六边形数、七边形数和八边形数——在其中各有一个代表。求这个集合的元素和。
  
### 062. 重排立方数(Cubic permutations)

立方数41063625=345<sup>3</sup>  可以重排为另外两个立方数：

**56623104=384<sup>3</sup>**
    
**66430125=405<sup>3</sup>**
    
实际上，41063625是重排中恰好有三个立方数的最小立方数。

求重排中恰好有五个立方数的最小立方数。
  
### 063. 幂与位数(Powerful digit counts)

5位数16807=7<sup>5</sup> 同时也是一个数的五次幂。同样的，9位数134217728=8<sup>9</sup> 同时也是九次幂。

有多少个n位正整数同时也是n次幂。

### 064. 奇周期平方根(Odd period square roots)

所有的平方根写成如下连分数表示时都是周期性重复的：

### 065. e的有理逼近(Convergents of e)

2的算术平方根可以写成无限连分数的形式：

### 066. 丢番图方程(Diophantine equation)

考虑如下形式的二次丢番图方程：

**x<sup>2</sup> – Dy<sup>2</sup> = 1**
      
举例而言，当D=13时，x的最小值出现在649<sup>2</sup> – 13×180<sup>2</sup> = 1。可以断定，当D是平方数时，这个方程不存在正整数解。

对于D= {2, 3, 5, 6, 7}分别求出x取最小值的解，我们得到：

**3<sup>2</sup> – 2×2<sup>2</sup>= 1**

**2<sup>2</sup> – 3×1<sup>2</sup> = 1**

**9<sup>2</sup> – 5×4<sup>2</sup> = 1**
     
**5<sup>2</sup> – 6×2<sup>2</sup> = 1**
      
**8<sup>2</sup> – 7×3<sup>2</sup> = 1**

因此，对于所有D ≤ 7，当D=5时x的最小值最大。

对于D ≤ 1000，求使得x的最小值最大的D值。
  
### 067. 最大路径和(进阶版)(Maximum path sum II)

从下面展示的三角形的顶端出发，不断移动到在下一行与其相邻的元素，能够得到的最大路径和是23。

```
   3
  7 4
 2 4 6
8 5 9 3
```

如上图，最大路径和为 3 + 7 + 4 + 9 = 23。

在文件[riangle.txt中](https://projecteuler.net/project/resources/p067_triangle.txt)一个100行的三角形，求从其顶端出发到达底部，计算能够得到的最大路径和。

**注**：这是第18题的进阶版。由于总路径一共有299条，穷举每条路经来解决这个问题是不可能的！即使你每秒钟能够检查1012条路径，全部检查完也需要两千万年。需要利用一个非常高效的算法才能解决这个问题。

### 068. “魔力”五边形环(Magic 5-gon ring)

从最外侧结点所填的数中最小的数（在这个例子中是4,3,2）开始，按顺时针方向连接数字。按照此种方式每个解都能被唯一地描述。

![image](https://projecteuler.net/project/images/p068_1.gif)

例如，上面这个解可以记作：

**4,3,2; 6,2,1; 5,1,3**

将环填满后，每条线上的总和一共有四种可能：9、10、11和12，总共有下面8种填法，见下图：

**Total	Solution Set**

**9:　4,2,3; 5,3,1; 6,1,2**

**9:　4,3,2; 6,2,1; 5,1,3**

**10:　2,3,5; 4,5,1; 6,1,3**

**10:　2,5,3; 6,3,1; 4,1,5**

**11:　1,4,6; 3,6,2; 5,2,4**

**11:　1,6,4; 5,4,2; 3,2,6**

**12:　1,5,6; 2,6,4; 3,4,5**

**12:　1,6,5; 3,5,4; 2,4,6**

把解集中的数字连接起来，可以构造一个9位数字串；对于三角形环来说，最大的数字串就是**2621513**。

在如下的“魔力”五边形环中

![image](https://projecteuler.net/project/images/p068_2.gif）

在其中填入1至10这10个数，根据不同的填写方式，可以组成16位或17位数字串。在“魔力”五边形环中，最大的16位数字串是。

### 069. 欧拉函数之比值(Totient maximum)


### 070. 欧拉函数之重排(Totient permutation)


### 071. 有序分数(Ordered fractions)

考虑形如n/d的分数，其中n和d均为正整数。如果n < d且其最大公约数为1，则该分数称为**最简真分数**。

如果将d ≤ 8的最简真分数构成的集合按大小升序列出，我们得到：

**1/8, 1/7, 1/6, 1/5, 1/4, 2/7, 1/3, 3/8, 2/5, 3/7, 1/2, 4/7, 3/5, 5/8, 2/3, 5/7, 3/4, 4/5, 5/6, 6/7, 7/8**

可以看出2/5是3/7直接左邻的分数。

将所有d ≤ 1,000,000的最简真分数按大小升序排列，求此时3/7直接左邻的分数的分子。

### 072. 分数个数(Counting fractions)

考虑形如n/d的分数，其中n和d均为正整数。如果n < d且其最大公约数为1，则该分数称为**最简真分数**。

如果将d ≤ 8的最简真分数构成的集合按大小升序列出，我们得到：

**1/8, 1/7, 1/6, 1/5, 1/4, 2/7, 1/3, 3/8, 2/5, 3/7, 1/2, 4/7, 3/5, 5/8, 2/3, 5/7, 3/4, 4/5, 5/6, 6/7, 7/8**

可以看出该集合中共有21个元素。

求出d ≤ 1,000,000的最简真分数构成的集合中共有多少个元素。

### 073. 区间内的分数个数(Counting fractions in a range)

考虑形如n/d的分数，其中n和d均为正整数。如果n < d且其最大公约数为1，则该分数称为**最简真分数**。

如果我们将d ≤ 8的最简真分数构成的集合按大小升序列出，我们得到：

**1/8, 1/7, 1/6, 1/5, 1/4, 2/7, 1/3, 3/8, 2/5, 3/7, 1/2, 4/7, 3/5, 5/8, 2/3, 5/7, 3/4, 4/5, 5/6, 6/7, 7/8**

可以看出在1/3和1/2之间有3个分数。

将d ≤ 12,000的最简真分数构成的集合排序后，在1/3和1/2之间有多少个分数。

### 074. 数字阶乘之链(Digit factorial chains)

145之所以广为人知，是因为它的各位数字的阶乘之和恰好等于本身：

**1! + 4! + 5! = 1 + 24 + 120 = 145**

169也具有这样的性质，从169开始不断地取各位数字的阶乘之和构成了具有三个数字的循环回到169；事实上，只存在三个这样的循环：

**169 ----> 363601 ----> 1454 ----> 169**

**871 ----> 45361 ----> 871**

**872 ----> 45362 ----> 872**

不难证明，从任意数字出发最终都会陷入循环。例如，

**69 ----> 363600 ----> 1454 ----> 169 ----> 363601 (----> 1454)**

**78 ----> 45360 ----> 871 ----> 45361 (----> 871)**

**540 ----> 145 (----> 145)**

从69开始可以得到一个拥有五个不重复项的链，但是从一个小于一百万的数出发能够得到的最长的无重复项链包含有60项。

从小于一百万的数出发，有多少条链恰好包含有60个不重复项。
  
### 075. 唯一整数边直角三角形(Singular integer right triangles)

只能唯一地折成整数边直角三角形电线的最短长度是12厘米，此外，还有很多长度的电线都只能唯一地折成整数边的直角三角形。如下所示：

**12厘米: (3,4,5)**

**24厘米: (6,8,10)**

**30厘米: (5,12,13)**

**36厘米: (9,12,15)**

**40厘米: (8,15,17)**

**48厘米: (12,16,20)**
  
相反地，有些长度的电线，比如20厘米，不可能折成整数边的直角三角形，而另一些长度则有多个解；例如，120厘米的电线可以折成三个不同的整数边直角三角形。

**120厘米: (30,40,50), (20,48,52), (24,45,51)**

记电线长度为L，对于L ≤ 1,500,000，有多少种取值只能唯一地弯折成整数边直角三角形。

### 076. 组合1 整数加法(Counting summations)

将5写成整数的和有下面6种不同的方式：

**1: 4 + 1**

**2: 3 + 2**

**3: 3 + 1 + 1**

**4: 2 + 2 + 1**

**5: 2 + 1 + 1 + 1**

**6: 1 + 1 + 1 + 1 + 1**
    
将100写成整数的和有多少种不同的方式。

### 077. 组合2 素数加法(Prime summations)

将10写成素数的和有5种不同的方式：

**1: 7 + 3**

**2: 5 + 5**

**3: 5 + 3 + 2**

**4: 3 + 3 + 2 + 2**

**5: 2 + 2 + 2 + 2 + 2**

写成素数的和有超过5000种不同的方式最小的数。

### 078. 硬币拆分(Coin partitions)

记p(n)是将n枚硬币拆分为堆的不同方式数。例如：五枚硬币有7种拆分成堆的不同方式，因此p(5)=7。

**1: OOOOO**

**2: OOOO O**

**3: OOO OO**

**4: OOO O O**

**5: OO OO O**

**6: OO O O O**

**7: O O O O O**

找出使p(n)能被一百万整除的最小n值。

### 079. 破解密码(Passcode derivation)

网上银行的一种密保手段是向用户询问密码中的任意三位字符。例如：如果用户密码是531278，询问第2、3、5位字符，正确回复应当是317。

文件[keylog.txt](https://projecteuler.net/project/resources/p079_keylog.txt)中包含了50个正确回复。

假设三个字符总是按顺序询问的，分析这个文本文件，给出这个未知长度的密码最短的一种可能。

### 080. 平方根展开(Square root digital expansion)

众所周知，如果一个自然数的平方根不是整数，那么就一定是无理数。这样的平方根的小数部分是无限不循环的。例如：2的平方根1.41421356237309504880…，它的前100位数字的和是475=1+4+1+…。

对于前100个自然数，求所有无理数平方根的前100位数字的总和。
  
### 081. 最小路径和(初级)  2个方向(Path sum: two ways)

在如下5\*5的数字矩阵中，只能向右或向下移动，从左上角到右下角的最小路径和为2427=131+201+96+342+746+422+121+37+331，路径已由红色数字标出：

### 082. 最小路径和(中级)  3个方向(Path sum: three ways)

在文件matrix.txt中包含了一个80*80的矩阵，求该矩阵的左上角到右下角的最小路径和。

### 083. 最小路径和(高级)  4个方向(Path sum: four ways)
  在如下5*5的数字矩阵中，从最左列任意一格出发，只能向右、向上或向下移动，到最右列任意一格结束的最小路径和为994=201+96+342+234+103+18，路径已由红色数字标出：
  
  
### 086. 长方体内最短直线路径(Cuboid route)

蜘蛛spider在一个6\*5\*3大小的长方体盒子的一角，而苍蝇fly则恰好位于其对角。沿着盒子的表面，从spider到fly最短的“直线”距离是**10=(6<sup>2</sup>+(3+5)<sup>2</sup>)<sup>1/2</sup>** ，其路径如下图所示：

![image](https://projecteuler.net/project/images/p086.gif)
  
然而，对于任意长方体，最短路径实际上一共有3种可能；而且，最短路径的长度也并不一定为整数。

当M=100时，若不考虑长方体的旋转，所有长、宽、高均不大于M且均为整数的长方体中，对角的最短距离是整数的恰好有2060个；100是使得该数目超过两千的最小M值；当M=99时，该数目为1975。

找出使得该数目超过一百万的最小**M值**。
  
### 087. 素数幂三元组(Prime power triples)

28是最小的可以表示为一个素数的平方，加上一个素数的立方，再加上一个素数的四次方的数。在小于50的数中，一共有4个数满足这一性质：

**28 = 2<sup>2</sup> +  2<sup>3</sup>  +  2<sup>4</sup> **

**33 = 3<sup>2</sup> + 2<sup>3</sup>  + 2<sup>4</sup> **

**49 = 5<sup>2</sup> + 2<sup>3</sup>  + 2<sup>4</sup> **

**47 = 2<sup>2</sup> + 3<sup>3</sup>  + 2<sup>4</sup> **

小于五千万的数中，可以这样表示的数的个数。
  
### 088. 积和数(Product-sum numbers)

若自然数N能够同时表示成一组至少包括两个自然数集合{a1, a2, … , ak}中元素的的积与和，也就是有

**N = a1 + a2 + … + ak = a1 × a2 × … × ak**

成立，则N被称为**积和数**。例如，6是积和数，因为6 = 1 + 2 + 3 = 1 × 2 × 3。

固定集合中元素的个数k，我们称满足上述性质的最小的N值为K的最小积和数。当k 分别为 2、3、4、5、6时，最小积和数如下所示：

**k=2: 4 = 2 × 2 = 2 + 2**

**k=3: 6 = 1 × 2 × 3 = 1 + 2 + 3**

**k=4: 8 = 1 × 1 × 2 × 4 = 1 + 1 + 2 + 4**

**k=5: 8 = 1 × 1 × 2 × 2 × 2 = 1 + 1 + 2 + 2 + 2**

**k=6: 12 = 1 × 1 × 1 × 1 × 2 × 6 = 1 + 1 + 1 + 1 + 2 + 6**

因此，对于2≤k≤6，所有的最小积和数的和为4+6+8+12 = 30。注意8只被计算了一次。已知对于2≤k≤12，所有最小积和数构成的无重复元素的集合是{4, 6, 8, 12, 15, 16}，这些数的和是61。

对于2≤k≤12000，所有最小积和数构成的无重复元素集合的元素和是。
  
### 089. 罗马数字表示法(Roman numerals)

要正确地用罗马数字表达一个数，必须遵循一些基本规则。尽管符合规则的写法有时会多于一种，但对每个数来说总是存在一种最好的写法。例如，数16就至少有下面的六种写法：

**IIIIIIIIIIIIIIII**

**VIIIIIIIIIII**

**VVIIIIII**

**XIIIIII**

**VVVI**

**XVI**

然而，根据规则，只有XIIIIII和XVI是合理的写法，而后一种因为使用了最少的数字而被认为是最好的写法。

在文件[roman.txt](https://projecteuler.net/project/resources/p089_roman.txt)中包含了一千个合理的罗马数字写法，但并不都是最好的写法；有关罗马数字的明确规则，可以参考关于[罗马数字](https://projecteuler.net/about=roman_numerals)。

求出将这些数都写成最有效的写法所节省的字符数。注意：可以假定文件中的所有罗马数字写法都不包含连续超过四个相同的字符。

### 090. 立方体数字对(Cube digit pairs)




### 091. 直角三角形个数(Right triangles with integer coordinates)

下图中，点P(x1, y1)、点Q(x2, y2)、原点O(0,0)构成直角坐标系中的三角形ΔOPQ：
  
![image](https://projecteuler.net/project/images/p091_1.gif)

当点P和点Q的所有坐标都在0到2之间，也就是说0 ≤ x1, y1, x2, y2 ≤ 2时，恰好能构造出如下所示的14个直角三角形。

![image](https://projecteuler.net/project/images/p091_2.gif)

如果0 ≤ x1, y1, x2, y2 ≤ 50，能构造出多少个直角三角形。

### 092. 数字链(Square digit chains)

将一个数的所有数字的平方相加得到一个新的数，不断重复直到新的数已经出现过为止，这构成了一条**数字链**。例如：

**44 --> 32 --> 13 --> 10 --> 1 --> 1**

**85 --> 89 --> 145 --> 42 --> 20 --> 4 --> 16 --> 37 --> 58 --> 89**

可见，任何一个到达1或者89的数字链都会循环下去。更令人惊奇的是，从任意数开始，最终都会到达1或89。

有多少个小于一千万的数最终会到达89。
  
### 093. 算术表达式(Arithmetic expressions)

使用集合{1, 2, 3, 4}中每个数字恰好一次以及"("，"+"，"−"，"\*"，" /"，")"四则运算和括号，可以得到不同的正整数。例如，

**8 = (4 * (1 + 3)) / 2**

**14 = 4 * (3 + 1 / 2)**

**19 = 4 * (2 + 3) − 1**

**36 = 3 * 4 * (2 + 1)**

使用集合{1, 2, 3, 4}，可以得到31个不同的数，其中最大值是36，以及1到28之间所有的数。

若使用包含有4个不同数字a < b < c < d的集合可以得到从1到n之间所有的数，求其中使得n最大的集合，并将集合元素写成字符串abcd的形式。

**注**：不允许直接把数字连起来，如12 + 34。

### 094. 近似等边三角形(Almost equilateral triangles)

### 095. 亲和数链(Amicable chains)


### 096. 数独(Su Doku)

**数独**是一种热门的谜题。它的起源已不可考，但它与欧拉发明的一种类似的谜题拉丁方阵之间有着千丝万缕的联系。数独是利用1~9的数字替换掉9\*9网格中的空白位置，使得每行、每列以及每个九宫格中恰好都包含数字1~9。如下是一个典型的数独谜题以及它的解答：


  
  一个构造精良的数独谜题应该包含有唯一解，且能够通过逻辑推断来解决，尽管有时可能必须通过“猜测并检验”来排除一些选项。寻找答案的复杂度决定了题目的难度；上面这个谜题被认为是一个比较简单的谜题，因为可以通过逻辑推断来解决它。
  
  在文件[sudoku.txt](https://projecteuler.net/project/resources/p096_sudoku.txt)中包含有50个不同难度的数独谜题，它们都只有唯一解。上面给出的示例就是文件中的第一个谜题。
  
解开这50个谜题，找出每个谜题解答左上角的三个数字并连接起来，给出这些数的和。例如：上述示例解答左上角的三个数字连接起来构成的数是483。  
  
### 097. 非梅森素数(Large non-Mersenne prime)

1999年人们发现了第一个超过100万位的素数，这是一个**梅森素数**，可以表示为2<sup>6972593</sup>−1，包含2,098,960位数字。在此之后，更多形如2<sup>p</sup>−1的梅森素数被发现，其位数也越来越多。

在2004年，发现了一个巨大的非梅森素数：28433×2<sup>7830457</sup>+1，包含2,357,207位数字。找出这个素数的最后十位数字。


### 098. 平方数重排(Anagramic squares)

如果单词CARE中的四个字母依次对应为1、2、9、6四个数字，我们得到了一个平方数：1296 = 362。神奇的是，使用同样的数字字母对应规则，重排后的单词RACE同样也构成了一个平方数：9216 = 962。我们称CARE和RACE为**重排平方单词对**，同时规定这样的单词对不允许第一个字母对应数字0或是不同的字母对应相同的数字。

在文件[words.txt](https://projecteuler.net/project/resources/p098_words.txt)中包含了将近2000个常见英文单词，找出其中所有的重排平方单词对，一个回文单词不视为它自己的重排。重排平方单词对所给出的最大平方数是多少。

**注**：所有的重排单词必须出现在给定的文本文件中。

### 099. 幂值比较(Largest exponential)

比较两个如2<sup>11</sup>和3<sup>7</sup>这样的幂值大小并不困难，任何计算器都能验证2<sup>11</sup> = 2048 < 3<sup>7</sup> = 2187。

然而，想要验证632382<sup>518061 </sup> > 519432<sup>525806</sup>就会变得非常困难，因为这两个数都包含有超过300万位数字。

在文件[base_exp.txt](https://projecteuler.net/project/resources/p099_base_exp.txt)有一千行，每一行有一对底数和指数，找出哪一行给出的幂值最大。文件的前两行就是上面给出的两个例子。

### 0100. 概率反推(Arranged probability)







