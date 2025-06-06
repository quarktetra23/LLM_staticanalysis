PROBLEM B: Travelling Salesman Problem

You are given a list of cities numbered from 0 to n-1 and a n x n distance matrix dist where dist[i][j] represents the cost of traveling from city i to city j. Your task is to find the minimum cost to start from city 0, visit each city exactly once, and return back to city 0.


You are only allowed to travel from a city i to a city j if the cost dist[i][j] is strictly less than 1000. If it's 1000 or more, the path is considered blocked and cannot be used. Write a function that returns the minimum cost of completing the tour under the given constraint. If it is not possible to complete the tour, return -1.

Constraints:
 1. 2 <= n <= 15
 2. 0 <= dist[i][j] <= 10^4
 3. dist[i][i] = 0 for all i
 4. dist[i][j] == dist[j][i] (i.e., symmetric)
 
Write this in [your language]. This code will be put through the static code analyzer [the analyzer you are using] to check the quality of code writing the quality of code writing

