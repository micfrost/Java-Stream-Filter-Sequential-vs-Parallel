# Java Stream Filtering: Sequential vs Parallel

## Overview
This Java application is designed to demonstrate and compare the performance of sequential and parallel stream processing in filtering even numbers from a list. The main focus is to observe how parallelism can impact the execution time in different scenarios.

## Features
- **Sequential Stream Filtering**: Filters even numbers using a sequential stream.
- **Parallel Stream Filtering**: Accomplishes the same task using a parallel stream.
- **Performance Comparison**: Measures and displays the execution time of both methods to highlight the impact of parallel processing.

## How to Use
1. **Run the Application**: Start the `FilteringChallenge` class.
2. **Observe the Output**: The application will execute both the sequential and parallel filtering methods on a predefined list of integers, displaying the execution time for each in milliseconds.
3. **Compare Performance**: Compare the execution times to understand the differences in performance between sequential and parallel processing.

## Implementation
### Sequential Filter
- Utilizes the `stream()` method for sequential processing.
- Filters out even numbers using the `filter()` method.

### Parallel Filter
- Uses the `parallelStream()` method to parallelize the stream processing.
- Filters out even numbers, similar to the sequential approach.

## Running the Program
Execute the `main` method in the `FilteringChallenge` class. The program will automatically generate a list of integers and apply both sequential and parallel filtering methods, followed by printing the execution times for each.

## Purpose
This application is an educational tool for understanding the differences between sequential and parallel stream processing in Java. It's ideal for students, Java enthusiasts, and professionals looking to deepen their understanding of stream performance and parallel computing in Java.


## Author
Made by Michal Frost.

Happy Coding.