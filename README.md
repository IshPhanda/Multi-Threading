# Matrix multiplication using Multi-Threading
Multiplication of matrix does take time surely. Time complexity of matrix multiplication is O(n^3) using normal matrix multiplication. And Strassen algorithm improves it and its time complexity is O(n^(2.8074)).

But, is there any way to improve the performance of matrix multiplication using the normal method. 

Multi-threading can be done to improve it. In multi-threading, instead of utilizing a single core of your processor, we utilizes all or more core to solve the problem.
We create different threads, each thread evaluating some part of matrix multiplication. 

Depending upon the number of cores your processor has, you can create the number of threads required. Although you can create as many threads as you need, a better way is to create each thread for one core.

## Usage
To run the code, simply execute the ***multi_threading_matrix_multiplication.py*** script. Make sure you have the required dependencies installed (NumPy, Matplotlib, Pandas).
