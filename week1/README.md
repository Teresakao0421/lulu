第一題
```py
function add(param1, param2) {
return (param1+param2)
param1=1
param2=2
   add (param1+param2)
}
```

第二題
```py
def centuryFromYear(year):
    return (year + 99) // 100
```   
第三題
```py
def checkPalindrome(inputString):
    return inputString == inputString[::-1]
```
[::-1] 顺序相反操作

[-1] 读取倒数第一个元素

[3::-1] 从下标为3（从0开始）的元素开始翻转读取

同样适用于字符串