# Task: Ресторант (Medium) - [HackerRank](<https://www.hackerrank.com/contests/sda-hw-2-2023/challenges/subarray123>)


### Statement:

Управителят на ресторант всеки ден си записвал на каква печалба е ресторантът в съответния ден. Тъй като не искал да влиза в подробности, той просто записвал по едно цяло число $N$. Обаче изведнъж разбрал, че от НАП, ще дойдат на следващия ден и той трябвало много бързо да си сортира печалбите, за да може лесно да излъже НАП за печалбата си. По това време обаче сортиращите алгоритми били много бавни и той не искал да сортира абсолютни всички печалби за всички дни. Затова решил да сортира възможно най-малката поредица, която ако бъде сортирана, то и цялата редица от печалби ще стане соритрана. Помогна му да намери дължината на тази редица.


### Input format

На първия ред се въвежда цяло число $N$

На втория ред, разделени с интервал се въвеждат $arr_i$ - печалбата за съответния пореден ден


### Constraints


$1 \le N \le 10^7$  

$-10^5 \le arr_i \le 10^5$


### Output format

Изведете 1 число, отговарящи на броя на дните, за които управителят трябва да сортира печалбите

#### Sample Input 0
```
7
2 6 4 8 10 9 15
```

#### Sample Output 0
```
5
```
