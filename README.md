Knapsack Algorithm Analysis
Overview
This program analyzes two variations of the Knapsack algorithm by calculating the number of steps required in different scenarios:

Greedy Fractional Knapsack: Uses a greedy approach to maximize the total value by taking fractions of items.
0/1 Knapsack (Dynamic Programming): Uses dynamic programming to find the optimal subset of items without allowing fractional selection.
How It Works
The program defines items with weights and values.
It runs both the Greedy Fractional Knapsack and 0/1 Knapsack algorithms on different capacities.
The results, including step counts and total values, are printed to the console.
Code Breakdown
fractionalKnapsack(): Implements the greedy fractional knapsack algorithm and counts the number of steps taken.
knapsack01(): Implements the 0/1 knapsack algorithm using dynamic programming and counts the number of steps.
analyzeKnapsack(): Runs both algorithms on different capacities and logs the results.
main(): Calls the analysis function to execute the program.
