这道题与昨天的题目非常相近，但是由于本题是“没有9”，所以会比“没有0”的题目简单一些。

因为数字是不可以有前导0的，所以“没有0”的N位数的第一位就会有9种数字1～9。但由于9进制的第一位数只能是1～8,所以我们要补0，让第一位数可以是0～8,从而转化成9进制，方便解题。

在本题中，由于我们去掉了9,所以第一位数是1～8,符合9进制的定义。所以本题直接进行9进制的转换即可。

代码如下：

```python
class Solution(object):
    def newInteger(self, n):
        u = 9 ** 10
        res = ''
        while u:
            res += str(n / u)
            n %= u
            u /= 9
        return int(res)
```
