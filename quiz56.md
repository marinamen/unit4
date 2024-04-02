
**QUIZ 056** 

✦　　　.　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 

56. You are starting a secret coding club with some friends and friends-of-friends. Not everyone knows each other, so you and your friends have decided to create a secret handshake.


　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦
**python code**

```.py
class Friends:
    def __init__(self, number):
        self.number=number
        self.handshake={
            0: "wink",
            1: "double blink",
            2: "close your eyes",
            3: "jump",
            4: "reverse"
        }

    def convert_binary(self):
        binary=''
        while self.number > 0:
            remainder=self.number % 2
            binary=str(remainder) + binary
            self.number = self.number // 2

        return binary[::-1]

    def create_handshake(self):
        binary = self.convert_binary()
        handshake = []
        for i in range(len(binary)):
            if binary[i] == "1":
                handshake.append(self.handshake[i])
        if "reverse" in handshake:
            handshake.remove("reverse")
            handshake = handshake[::-1]
        return handshake

f=Friends(9)
print(f.create_handshake())
f=Friends(31)
print(f.create_handshake())
f=Friends(19)
print(f.create_handshake())

```
**proof of work**　　. 　 ˚　.　　　　　 . ✦　　　 　˚　　　　 . ★⋆. ࿐࿔ 
　　　.   　　˚　　 　　*　　 　　✦　　　.　　.　　　✦　˚ 　　　　 ˚　.˚　　　　✦

![](https://github.com/marinamen/unit4/blob/main/images/Screenshot%202024-04-02%20at%2022.53.00.png)
