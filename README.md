# SumEqualsZero

This code is designed to find a subarray with a sum of zero in an array. It takes an input array from the user and checks all possible subarrays to find one with a sum of zero.

## Algorithm

1. Read the size of the array from the user.
2. Read the array elements from the user.
3. Create an empty ArrayList `sumZero` to store the elements of the subarray with a sum of zero.
4. Iterate over each element of the array using two nested loops to generate all possible subarrays.
5. For each subarray, calculate the sum and store the elements in `sumZero`.
6. If the sum of the subarray is zero, print the elements of `sumZero` and return.
7. If no subarray with a sum of zero is found, print "No Elements found".

## Complexity Analysis

The time complexity of this code is O(n^3) because it uses three nested loops to iterate over all possible subarrays. The space complexity is O(n) because it uses an ArrayList of size n to store the elements of the subarray with a sum of zero.

## Usage

To use this code:

1. Copy the code into a Java file (e.g., `Main.java`).
2. Compile the code using a Java compiler.
3. Run the compiled code.
4. Enter the size of the array when prompted.
5. Enter the array elements separated by spaces.
6. The code will output the elements of a subarray with a sum of zero, if found.
