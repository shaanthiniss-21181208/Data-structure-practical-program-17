class Solution:
    def isPowerofTwo(self, n):
        
        if n <= 0:
            return False
        
        while n % 2 == 0:
            n //= 2
        
        return n == 1# Data-structure-practical-program-17
