# CQ8

Staircase
time complexity- O(n^2) becuase of nested for loops
space complexity- O(1) constant space

Alternating characters
time complexity- O(n^2) because the recusion iterates through the string one character at a time which is O(n) time complexity, 
but .substring() also has an O(n) time complexity so the total time complexity is O(n^2)
space complexity- O(n) becuase each recursive call adds a layer to the call stack, and substring() has a space complexity of O(1)
recursive definition- base case- the string is one or less characters long, if s.chatAt(0) is the same as  s.chatAt(0)
we increment the counter and recusively calls itself excluding the first character, if s.chatAt(0) and s.chatAt(0) are not the 
same we do the same thing without incrementing the counter
