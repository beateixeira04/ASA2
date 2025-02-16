# ASA2
Segundo projeto da cadeira de análise e síntese de algoritmos - 2º ano de faculdade

Metro Connectivity Index

Description
This project analyzes the efficiency of a metro network by computing the metro connectivity index (mc). The index is defined as the maximum number of line changes required to travel between any two stations in the network. The program determines the minimum number of transfers needed for all station pairs and returns the worst-case scenario.

Input Format

    An integer n – number of stations (n ≥ 2).
    An integer m – number of connections (m ≥ 0).
    An integer l – number of lines (l ≥ 0).
    m lines of input, each containing three integers x y l, meaning station x and station y are directly connected by line l.

Output Format

    An integer s, representing the metro connectivity index:
        If no line changes are needed, output 0.
        If there exists at least one pair of disconnected stations, output -1.
        Otherwise, output the maximum number of line changes needed between any two stations.

Example

Input:
7 8 3
1 2 1
2 3 1
3 4 2
4 5 2
5 6 3
6 7 3
1 7 1
2 6 2

Output:
2

Compilation & Execution
Compile the program using:
g++ -std=c++11 -O3 -Wall main.cpp -o metro_connectivity

Run the program with:
./metro_connectivity < input.txt

Grading:
This project was graded 20/20, indicating a correct and efficient implementation.
