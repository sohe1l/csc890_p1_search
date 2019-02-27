Soheil Ansari
Student ID: 917951156

I have implemented each problem according to the requirements. The problems 1 and 2 were very trivial and only basic DFS and BFS was required. The only challenge was understanding the structure of the code and existing functions. Question 3 was also relatively simple and the trick was to use a priority queue and pass the cost. To solve problem 4 also I have used a priority queue, except that I have used forward and backward cost for the priority queue.

The tricky part about problem 5 was to figure out how to define the state. At first, I tried to figure out which corners have been visited by trying to access the actions which did not work. Eventually, I figured I should store that piece of info in the state. To solve problem 6 I used a basic function to start estimating from the closest unvisited corner and add all the distances.

Problem 7 was the most challenging problem. I used the function to estimate by adding the distance of Pacman to the closest food and sum of the smallest distance of each food to the closest food and that reduced the expanded node to about 8100. For problem 8 I used the basic BFS algorithm.


The assignemnt took about three days.