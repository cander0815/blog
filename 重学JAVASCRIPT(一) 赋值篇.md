# 重学JAVASCRIPT(一): 赋值篇

## 变量

在JavaScript中的变量是松散类型, 即 同一个变量可以用来存储不同类型的值

```javascript
	var a = 1;
	a = 'hello word'; // 不推荐前后存储不同类型的值
```

在变量 `a`中初始化了一个数字类型的`1`, 后有在第二行为变量`a`中赋值了字符串`hello word`;  这样的写法在JavaScript中是完全没有问题, 但是不建议过多的去给变量赋值不同的类型的值, 有可能会导致自己的逻辑混乱;

## 声明一个变量

