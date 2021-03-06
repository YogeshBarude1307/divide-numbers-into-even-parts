We need the ability to divide an unknown integer into a given number of even parts — or at least as even as they can be. The sum of the parts should be the original value, but each part should be an integer, and they should be as close as possible.

Complete the function so that it returns an array of an integer representing the parts. Ignoring the order of the parts, there is only one valid solution for each input to your function!

Also, there is no reason to test for edge cases: the input to your function will always be valid for this challenge.

Specification
splitInteger(num, parts) Divides an integer into an "even as can be" number of parts.

Parameters
num: Number - The number that should be split into equal parts
parts: Number - The number of parts that the number should be split into

Return Value
Array - An array of parts, with each index representing the part and the number contained within it representing the size of the part. The parts will be ordered from smallest to largest.

Examples
num parts Return Value Completely even parts example 10 5 [2,2,2,2,2] Even as can be parts example 20 6 [3,3,3,3,4,4]
  
