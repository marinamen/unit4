
**QUIZ 053** 

✦　　　.　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 

53.  Create a class palNum with a method get_pal_list() that returns a list with the palindromic numbers inside a range A, B inclusive. A and B are class attributes.


　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦
**python code**

```.py
class palNum:
    def __init__(self, A:int, B:int):
        self.A = A
        self.B = B
    def get_pal_list(self, A, B):
        f = []
        for number in range(A, B+1):
            reverseS = ""
            print(number)
            s=str(number)
            for i in range(len(s)-1,-1,-1):
                reverseS += s[i]
            if s == reverseS:
                f.append(s)
        return f



text=palNum(A=10,B=199)
print(text.get_pal_list(A=10,B=199))
```
**proof of work**　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 
　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦

![](https://github.com/marinamen/unit3/blob/main/images/Screenshot%202024-02-19%20at%2008.38.22.png)
