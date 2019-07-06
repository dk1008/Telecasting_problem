# Telecasting_problem

#Something to Watch

You’re given n shows, each with a fixed start time (s) and an end time (e). Each show is telecasted on a different channel. Find the total duration during which at least one show is being telecasted.


#Constraints
1 <= t <= 10^3

1 <= n<= 10^4

1 <= e - s (in seconds) <= 24 * 60 * 60


Time format is a 24 hour clock with start of the day as 00:00:00 and end as 24:00:00.


#Input Format

The first line contains a single integer t, denoting the number of test cases. 
The first line of each test case contains a single integer n denoting the number of shows (and channels). 
Following n lines contains the start s and end e for each show space separated.

#Output Format

For each test case print the total duration.

#Sample Input
10
3
07:00:00 09:30:00
09:00:00 10:30:00
11:00:00 11:30:00
1
00:00:00 24:00:00
1
20:30:00 21:00:00
1
00:00:00 23:59:59
1
00:00:01 23:59:59
2
12:00:00 13:00:00
14:00:00 21:00:00
3
12:00:00 24:00:00
14:00:00 22:00:00
16:00:00 20:00:00
8
18:30:00 21:30:00
07:00:00 23:00:00
14:30:00 22:00:00
01:30:00 11:30:00
07:30:00 13:00:00
22:30:00 23:30:00
17:30:00 18:00:00
01:00:00 02:30:00
4
01:00:00 02:00:00
03:00:00 04:00:00
04:00:00 12:00:00
15:00:00 24:00:00
5
13:00:00 24:00:00
00:00:00 08:00:00
14:00:00 24:00:00
08:00:00 14:00:00
00:00:00 13:00:00


#Sample Output
04:00:00
24:00:00
00:30:00
23:59:59
23:59:58
08:00:00
12:00:00
22:30:00
19:00:00
24:00:00
