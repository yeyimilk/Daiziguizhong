# 每日一题 180611

## 托米去购物

链接：https://www.nowcoder.com/acm/contest/111/D       
来源：牛客网

此时的托米老师已经出任CEO，迎娶白富美，走向了人生巅峰！于是这个暑假，托米老师打算在北京一个偏僻的小农村里度过他的假期。

由于这里什么都没有，于是他去超市选了很多生活用品，更多的是吃的，然后推着堆满零食的购物车到柜台等待结账。

当然，我们都知道他的钱包里有很多钱。但是，作为一名为生活精打细算的男孩子，他更愿意使用其他支付方式如：饭券，礼券，不同类型的优惠券等。但是饭券只能用于购买食物，而礼券通常只限于某种类型的礼物。

现在给你托米购物车中物品的数量N和每件物品的价格。也会给出他钱包中的代金券数量M以及允许使用的信息 。

在为他的购物付款时，托米可能使用代金券的金额超过他所购物品的成本。也可以在多张代金券之间拆分商品的成本，并使用代金券支付多件商品。

请你计算托米需要为购物支付的额外现金的最小金额。

## 输入描述

输入的第一行包含一个整数T，用于指定测试用例的数量。

每个测试用例前面都有一个空白行。

每个测试用例从包含两个正整数N(物品数量)和M(券数量)的行开始。

接下来一行包含N个数字，第i个数字表示托米购物车里第i件物品的价格。

接下来一行包含M个数字，第i个数字表示第i张券的金额。

接下来有M行，当中的第 i 行描述第 i 张卷可以买哪些商品。每行的第一个数字是 K,代表第 i 张卷可以为 K 件商品付款，接下来还有 K 个数，是这 K 件商品的编号

T≤40 N≤200 M≤1200

满足M>200的数据保证只有一组

单个物品金额和单张优惠券金额≤10000

## 输出描述

对于每个测试用例输出数字，表示托米需要支付多少现金。

## 示例
```
> INPUT
1

3 2
15 20 10
20 30
3 1 2 3
1 3

> OUTPUT
15
```

## 请我喝一杯可乐

![](https://raw.githubusercontent.com/Inapt19/Resource/master/bonus_QR.jpg)
![](https://raw.githubusercontent.com/Inapt19/Resource/master/wechat_bonus_qr.jpg)

## 待字闺中算法讨论微信群

微信群算法讨论，娱乐比赛开黑等你加入。

![](https://raw.githubusercontent.com/Inapt19/Resource/master/wechat_QR.jpg)