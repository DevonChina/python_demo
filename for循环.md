# for循环

for循环可以遍历任何序列的项目，比如遍历一个字符串的所有字母或者遍历一个列表中所有元素，还是老规矩，废话不多说直接整代码：

```
#!/usr/bin/env python3
#coding:utf-8

for letter in 'park':
	print('park 中的字母有：',letter)

zoo = ['monkey','tiger','lion','giraffe']
for animal in zoo:
	print('动物有',animal)
```

代码的含义就是：前半部分是执行打印输出“park“这个词中里有哪些字母组成；后边部分是打印出动物园里动物有哪些；咋样for循环其实也就那么回事吧！

### 通过序列索引迭代

比上面for循环增加一个难度，我们还能通过序列索引迭代来实现，撸代码：

```
#!/usr/bin/env python3
#coding:utf-8

zoo = ['monkey','tiger','lion','giraffe']
for index in range(len(zoo)):
	print('动物有：', zoo[index])
	
```

上面的实例中我们其实用到了两个方法，他们是Python的内置函数len()与range()
函数len()返回列表的长度
函数rannge()返回一个序列数
大家敲一下我贴出来的代码运行输出看看效果，代码多撸才是硬道理



