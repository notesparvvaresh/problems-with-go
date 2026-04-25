# Go Algorithm Practice

This repository contains a collection of small algorithm and data structure exercises written in Go.

The goal of the project is simple:
- practice problem solving,
- improve Go skills with small standalone programs,
- build familiarity with common interview-style algorithms.

Each folder contains one independent example with its own `main` function, so you can run them one by one without setting up a larger project.

## What is included

Current examples in this repository:

- `BFS` - Breadth-First Search on a graph
- `DFS` - Depth-First Search on a graph
- `binarySearch` - Binary search in a sorted array
- `linearSearch` - Linear search
- `jumpSearch` - Jump search
- `bubbleSort` - Bubble sort
- `selectionSort` - Selection sort
- `insertionSort` - Insertion sort
- `mergeSort` - Merge sort
- `quickSort` - Quick sort folder exists and appears to be a work in progress
- `factorialIterative` - Iterative factorial
- `factorialRecursive` - Recursive factorial
- `GCD` - Greatest common divisor using Euclid's algorithm
- `MaxMin` - Find maximum and minimum values in an array
- `isPrime` - Prime number check
- `isPalindrome` - Palindrome check
- `isAnagram` - Anagram check
- `isSorted` - Check whether an array is sorted
- `reverseNumber` - Reverse the digits of a number
- `removeDuplicates` - Remove duplicate values from an array
- `runLengthEncoding` - Simple run-length encoding
- `hash` - Basic string hashing example
- `Counting_Element_Frequencies` - Count repeated elements in an array

## Requirements

You only need Go installed on your machine.

To check that Go is available:

```bash
go version
```

## How to run an example

Move into the folder for the example you want to try, then run its Go file.

```bash
cd factorialRecursive
go run factorialRecursive.go
```

Another example:

```bash
cd binarySearch
go run binarySearch.go
```

Because each program is standalone, you can run any folder in the same way.

## Project structure

The repository is organized as a set of small directories:

```text
problems-with-go/
|- BFS/
|- DFS/
|- binarySearch/
|- bubbleSort/
|- factorialRecursive/
|- mergeSort/
|- ...
```

Each directory usually contains:
- one `.go` file,
- a small implementation,
- a `main` function with sample input and output.

## Why this repo exists

This project is useful for:
- learning basic algorithms in Go,
- reviewing core programming concepts,
- practicing before coding interviews,
- keeping simple algorithm examples in one place.

## Notes

- Most examples are intentionally small and beginner-friendly.
- The programs are written as separate examples rather than as one reusable package.
- Some implementations may be expanded or refined over time.

## Contributing

Suggestions and improvements are welcome.

If you want to contribute:
1. fork the repository,
2. add a new algorithm or improve an existing one,
3. open a pull request.

## License

This project includes a `LICENSE` file. See `LICENSE` for details.

Built with Go and a lot of practice.
