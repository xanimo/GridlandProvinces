* *Please note there's an issue running the repl.it on mobile phones.  If interested in playing with the repl.it please do it on a computer*

![GridlandProvinces](https://raw.githubusercontent.com/xanimo/images/master/logo.png?token=AHTBONAJ6MJ3U7ZT32YFAZK7NZOV6)

# Gridland Provinces
<a href="https://www.hackerrank.com/challenges/gridland-provinces/problem" target="_blank"><img src="https://raw.githubusercontent.com/xanimo/images/master/rank.png?token=AHTBONB3K6AK4LFFRVEFU2C7NZPJS" alt="first ever fully accepted solution to this problem written in javascript!"></a>

### Overview
The Kingdom of Gridland contains **P** provinces. Each province is defined as a **2 x N** grid where each cell in the grid represents a city. Every cell in the grid contains a single lowercase character denoting the first character of the city name corresponding to that cell.

From a city with the coordinates **(i, j)**, it is possible to move to any of the following cells in **1** unit of time (provided that the destination cell is within the confines of the grid):
*  **(i - 1, j)**
*  **(i + 1, j)**
*  **(i, j - 1)**
*  **(i, j + 1)**

A knight wants to visit all the cities in Gridland. He can start his journey in any city and immediately stops his journey after having visited each city at least once. Moreover, he always plans his journey in such a way that the total time required to complete it is minimum.

After completing his tour of each province, the knight forms a string by concatenating the characters of all the cells in his path. How many distinct strings can he form in each province?

#### Input Format

The first line contains a single integer, **P**, denoting the number of provinces. The **3 * P** subsequent lines describe each province over the following three lines:
The first line contains an integer, **N**, denoting the number of columns in the province.
Each of the next two lines contains a string, **S**, of length **N** denoting the characters for the first and second row of the province.

#### Constraints
*  **1 ≤ P ≤ 15**
*  **1 ≤ N ≤ 600**
*  **Si  ϵ  {a - z}**

#### Output Format

For each province, print the number of distinct strings the knight can form on a new line.

#### Sample Input
```
3
1
a
a
3
dab
abd
5
ababa
babab
```
#### Sample Output
```
1
8
2
```
#### Explanation

Province 0:

![query 0](https://s3.amazonaws.com/hr-challenge-images/20359/1466406002-188ce9a517-hackerland.png)

The knight can only form one string (aa), so we print **1** on a new line.

Province 1:

![query 1](https://s3.amazonaws.com/hr-challenge-images/20359/1466406112-3eea23fe0a-hackerland1.png)

The knight can form eight different strings (abdbad, adabdb, badabd, bdbada, dababd, dabdba, dbabad, and dbadab), so we print **8** on a new line.

Province 2:

![query 2](https://s3.amazonaws.com/hr-challenge-images/20359/1466406248-cb1a6f25b4-hackerland2.png)

The knight can form two different strings (ababababab and bababababa), so we print **2** on a new line.

## Try it
If you'd care to play around with this code please check out the [corresponding repl.it](https://repl.it/@xanimo/GridlandProvinces#index.js).  And if you'd care to follow or get in touch here is my [HackerRank profile](https://www.hackerrank.com/profile/bluezr).

<a href="https://repl.it/@xanimo/GridlandProvinces#index.js" target="_blank"><img src="https://raw.githubusercontent.com/xanimo/images/master/replit.svg?token=AHTBONGAPFTTFFRQALQZLCK7NZ3WG" width="150"/></a> <a href="https://www.hackerrank.com/profile/bluezr" target="_blank"><img src="https://raw.githubusercontent.com/xanimo/images/master/hrlogo.svg?token=AHTBONALBFYHHXNAG4MQE427NZZK2" width="250"/></a> 
