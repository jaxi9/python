# python
study new python 
变量：List
#!/usr/bin/python


#list
list1 = ['physics', 'chemistry', 1997, 2000]
list2 = [1, 2, 3, 4, 5, 6, 7 ]
print "list1[0]: ", list1[0]
print "list2[1:5]: ", list2[1:5]
以上实例输出结果：
list1[0]:  physics
list2[1:5]:  [2, 3, 4, 5]


访问元组
元组可以使用下标索引来访问元组中的值，如下实例:

#!/usr/bin/python

tup1 = ('physics', 'chemistry', 1997, 2000);
tup2 = (1, 2, 3, 4, 5, 6, 7 );

print "tup1[0]: ", tup1[0]
print "tup2[1:5]: ", tup2[1:5]
以上实例输出结果：

tup1[0]:  physics
tup2[1:5]:  (2, 3, 4, 5)





访问字典里的值
把相应的键放入熟悉的方括弧，如下实例:

实例
#!/usr/bin/python
 
dict = {'Name': 'Zara', 'Age': 7, 'Class': 'First'};
 
print "dict['Name']: ", dict['Name'];
print "dict['Age']: ", dict['Age'];
以上实例输出结果：

dict['Name']:  Zara
dict['Age']:  7
如果用字典里没有的键访问数据，会输出错误如下：

实例
#!/usr/bin/python
 
dict = {'Name': 'Zara', 'Age': 7, 'Class': 'First'};
 
print "dict['Alice']: ", dict['Alice'];
以上实例输出结果：

dict['Alice']: 
Traceback (most recent call last):
  File "test.py", line 5, in <module>
    print "dict['Alice']: ", dict['Alice'];
KeyError: 'Alice'
 
 
 #!/usr/bin/python
# -*- coding: UTF-8 -*-
 
# 定义函数
def printme( str ):
   "打印任何传入的字符串"
   print str;
   return;
 
# 调用函数
printme("我要调用用户自定义函数!");
printme("再次调用同一函数");
