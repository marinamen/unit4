
**QUIZ 052** 

✦　　　.　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 

52. Create a Bicycle class with a Wheel class as its attribute using composition. 🚲


　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦
**python code**

```.py

class wheel:
    def __init__(self, wsize):
        self.wsize = wsize

    def get_size(self):
        return f"the wheel size is {self.wsize}"

    def get_perimeter(self):
        calc1=self.wsize * 3.14 * 0.0254
        return f" the wheel perimeter is {calc1} meters"

    def get_km(self,):
        calc2 = (self.wsize *  0.0254)*3.14 *2  / 1000
        return f"{calc2} km per rotation"


class bicycle:
    def __init__(self, wsize, material):
        self.wheel = wheel(wsize)
        self.material = material

    def ride(self):
        return f" the wheel size is {self.wheel.wsize} inches & the material of the frame is {self.material}"


x=bicycle(wsize=26,material="aluminium")
print(x.ride())

y = wheel(wsize = 26)
print(y.get_km())

```
**proof of work**　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 
　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦

![](https://github.com/marinamen/unit4/blob/main/images/Screenshot%202024-04-02%20at%2022.48.02.png)
