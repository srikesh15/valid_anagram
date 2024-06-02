# valid_anagram
#from typing import Counter
from collections import Counter

class Solution:
    s = input()
    t = input()
    def isAnagram(s, t):
        #return sorted(s) == sorted(t)
        return Counter(s) == Counter(t)
    
    print(isAnagram(s, t))

        
