<!--

In the enchanted realm of literary adventures, our hero, Tom, is battling the formidable Ashe with his magical poison attacks! 
Each time Tom strikes Ashe, she gets poisoned for exactly duration seconds. Formally, an attack at second t means Ashe is poisoned during the inclusive time interval [t, t + duration - 1]. 
If Tom attacks again before the poison effect ends, the timer for it is reset, and the poison effect will end duration seconds after the new attack.

You are given a non-decreasing list timeSeries, where timeSeries[i] denotes the moments Tom attacks Ashe, and an integer duration.
Write a function total_poisoned_time(timeSeries, duration) to calculate the total number of seconds that Ashe is poisoned.

Note: In the magical world of books and novels, time can be both a friend and a foe. Ashe must endure the poisoned pages of her story, and your task is to calculate her total poisoned time. 
May your calculations be swift and accurate, guiding our hero Tom to victory! 📚🔮

Input Format:
- Size of time series array
- A list of integers timeSeries representing the moments when Tom attacks Ashe.
- An integer duration representing the duration of the poison effect.
- The timeSeries list is sorted in non-decreasing order.

Constraints:
(1 <= timeSeries.length <= 10^4) (0 <= duration <= 10^7)

Output Format:
An integer representing the total number of seconds that Ashe is poisoned.

Sample Input 0:
2
1 4
2

Sample Output 0:
4

Explanation 0:
Tom's attacks on Ashe go as follows: - At second 1, Tom attacks, and Ashe is poisoned for seconds 1 and 2. - At second 4, Tom attacks, and Ashe is poisoned for seconds 4 and 5. 
Ashe is poisoned for seconds 1, 2, 4, and 5, which is 4 seconds in total.

Sample Input 1:
2
1 2
2

Sample Output 1:
3

Explanation 1:
Tom's attacks on Ashe go as follows: - At second 1, Tom attacks, and Ashe is poisoned for seconds 1 and 2. - At second 2, however, Tom attacks again and resets the poison timer. 
Ashe is poisoned for seconds 2 and 3. Ashe is poisoned for seconds 1, 2, and 3, which is 3 seconds in total.

-->

# iitrix-24
A repository containing problem statements for The Solver's Showdown Event

## Hello fellow Solvers!
Welcome to "The Solvers Showdown" GitHub repository!

This repo acts as the hub where you'll find all the problem statements for "The Solvers Showdown" event. 
You're in the right place to test your skills and dive into some exciting problem-solving adventures. Feel free to explore everything else in this repository to get your problem statements. 

Good luck, and let the solving begin!
