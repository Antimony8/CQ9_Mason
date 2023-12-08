# Weighted Uniform Strings Time Complexity
The time complexity is O(N + Q), where N is the length of the input string s and Q is the number of queries. The function iterates through the characters of the string once to calculate the weights and then processes each query in constant time.

# Weighted Uniform Strings Space Complexity
The space complexity is O(N), where N is the length of the input string s. The function uses a HashSet to store unique weights of uniform contiguous substrings. In the worst case, each character contributes a unique weight, resulting in space proportional to the length of the input string.

# Mini Max Time Complexity
The time complexity is O(n), where n is the size of the input list arr. This is because the algorithm iterates through each element in the list once to calculate the total sum. it also finds the minimum and maximum values in the list, which takes linear time. Therefore, the overall time complexity is dominated by the linear iteration through the input list.

# Mini Max Space Complexity
The space complexity of this solution is O(1) because the algorithm uses a constant amount of additional space that does not depend on the size of the input. It only uses variables to store the total sum, maximum sum, and minimum sum.
