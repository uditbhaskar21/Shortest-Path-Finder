# Shortest-Path-Finder
I have created a web app for finding the most optimal path and minimum distance of path travelled.

# Technologies Used
1.Python
2.JavaScript
3.Flask
4.HTML
5.CSS
6.Deployed using Azure

# How to enter Input
1. Firstly you have to enter the number of cities, Let's say number of cities are equal to N (Cities=N).
2. Now you have to enter N*N number of inputs as distance between cities.
# Format of Input
1. You have to enter distance in form of numbers seperated by space.
Eg: Let ther be four cities A, B, C, D.
Distances between A-A = 0, A-B = 10, A-C = 15, A-D = 20
                  B-A = 10, B-B = 0, B-C = 30, B-D = 5
                  C-A = 15, C-B = 20, C-C = 0, C-D = 9
                  D-A = 20, D-B = 5 , D-C = 9, D-D = 0
                  
 For this Information Input will be = 0 10 15 20 10 0 30 5 15 20 0 9 20 5 9 0
 
 # Output
 The Shortest Path is : 1>2>3>4>1 and the Minimum Distance is : 9
 # Random Test Cases
 Input 1 : Cities = 1
 O/P = "Path is not possible !"
 
 Input 2 : Cities = 2
 Distance = 0 15 7 0
 O/P = "The Shortest Path is : 1>2>1 and the Minimum Distance is : 22"
 
 Input 3 : Cities = 5
 Distance = 0 5 8 10 2 5 0 15 9 6 8 15 0 3 12 10 9 3 0 4 2 6 12 4 0
 O/P = "The Shortest Path is : 1>2>5>4>3>1 and the Minimum Distance is : 26"
 
