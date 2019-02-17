# Python Week1 Assignment
## Q1 <a name="FN1">1</a>
One hot summer day Pete and his friend Billy decided to buy a watermelon. They chose the biggest and the ripest one, in their opinion. After that the watermelon was weighed, and the scales showed w kilos. They rushed home, dying of thirst, and decided to divide the berry, however they faced a hard problem.

Pete and Billy are great fans of even numbers, that's why they want to divide the watermelon in such a way that each of the two parts weighs even number of kilos, at the same time it is not obligatory that the parts are equal. The boys are extremely tired and want to start their meal as soon as possible, that's why you should help them and find out, if they can divide the watermelon in the way they want. For sure, each of them should get a part of positive weight.

### Input
The first (and the only) input line contains integer number w (1 ≤ w ≤ 100) — the weight of the watermelon bought by the boys.
### Output
Print **YES**, if the boys can divide the watermelon into two parts, each of them weighing even number of kilos; and **NO** in the opposite case.

**Examples**

__Input__

`8`

__Output__

`YES`

For example, the boys can divide the watermelon into two parts of 2 and 6 kilos respectively (another variant — two parts of 4 and 4 kilos).

## Q2 <a name="FN2">2</a>
Theatre Square in the capital city of Berland has a rectangular shape with the size n × m meters. On the occasion of the city's anniversary, a decision was taken to pave the Square with square granite flagstones. Each flagstone is of the size a × a.

What is the least number of flagstones needed to pave the Square? It's allowed to cover the surface larger than the Theatre Square, but the Square has to be covered. It's not allowed to break the flagstones. The sides of flagstones should be parallel to the sides of the Square.

### Input
The input contains three positive integer numbers in the first line: n,  m and a (1 ≤  n, m, a ≤ 109).
### Output
Write the needed number of flagstones.
### Examples
__Input__

`6 6 4`

__Output__

`4`

## Q3 <a name="FN3">3</a>

Andrew, Dmitry and Michal are all grapes' lovers, however their preferences of grapes are different. To make all of them happy, the following should happen:

+ Andrew, Dmitry and Michal should eat at least x, y and z grapes, respectively.
+ Andrew has an extreme affinity for green grapes, thus he will eat green grapes and green grapes only.
+ On the other hand, Dmitry is not a fan of black grapes — any types of grapes except black would do for him. In other words, Dmitry can eat green and purple grapes.
+ Michal has a common taste — he enjoys grapes in general and will be pleased with any types of grapes, as long as the quantity is sufficient.

Knowing that his friends are so fond of grapes, Aki decided to host a grape party with them. He has prepared a box with a green grapes, b purple grapes and c black grapes.

However, Aki isn't sure if the box he prepared contains enough grapes to make everyone happy. Can you please find out whether it's possible to distribute grapes so that everyone is happy or Aki has to buy some more grapes?

It is not required to distribute all the grapes, so it's possible that some of them will remain unused.
### Input
The first line contains three integers 
`x, y and z (1≤x,y,z≤10^5)` — the number of grapes Andrew, Dmitry and Michal want to eat.

The second line contains three integers `a, b, c (1≤a,b,c≤10^5)` — the number of green, purple and black grapes in the box.
### Output
If there is a grape distribution that allows everyone to be happy, print **"YES"**, otherwise print **"NO"**.
### Examples
__Input__

`1 6 2`

`4 3 3`

__Output__

`YES`

__Input__

`5 1 1`

`4 3 2`
__Output__

`NO`

In the first example, there is only one possible distribution:
Andrew should take 1 green grape, Dmitry should take 3 remaining green grapes and 3 purple grapes, and Michal will take 2 out of 3 available black grapes.

In the second test, there is no possible distribution, since Andrew is not be able to eat enough green grapes.

***
<sup>[1](#FN1) [codeforces](http://codeforces.com/problemset/problem/4/A)</sup>
<sup>[2](#FN2) [codeforces](http://codeforces.com/problemset/problem/1/A)</sup>
<sup>[3](#FN3) [codeforces](http://codeforces.com/problemset/problem/1114/A)</sup>