
**QUIZ 054** 

✦　　　.　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 

54. Create a class rainDrops with a method pour(n:int) that convert the number n into its corresponding raindrop sounds.


　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦
**python code**

```.py
class rainDrop:
    out=''
    def pour(self,n:int):
        m={3:'i',5:'a',7:'o'}
        out=''
        for k,v in m.items():
            out+= (n% k==0)*f'pl{v}ng'
        out+=str(n)*(len(out)== 0)
        return out

text=rainDrop()
print(text.pour(n=3))

```
**proof of work**　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 
　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦

![](https://github.com/marinamen/unit4/blob/main/images/Screenshot%202024-04-02%20at%2022.48.28.png)

**uml diagram**　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 
　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦

![](https://github.com/marinamen/unit4/blob/main/images/Untitled%20(13).jpg)

I meant to put rainDrop
