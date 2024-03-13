- Create a empty hash map
- for each element "n" in the array, if (target - n) belongs to the hash map then return [idx(target-n), idx(n)]
- else append n:idx to the hash map

Time Complexity: O(n)
Space Complexity: O(n-1)
