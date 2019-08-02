

```python
from matplotlib import pyplot as plt
from matplotlib import style
style.use('ggplot')
X=[1,2,5,6]
Y=[5,7,8,9]
X2=[3,4,7,8]
Y2=[1,2,3,9]
plt.plot(X,Y,'g', label='lineone',linewidth=5)
plt.plot(X2,Y2,'c', label='linetwo',linewidth=5)
plt.title('Vaa_smart information')
plt.xlabel('x axis sales')
plt.ylabel('y axis customers')
plt.legend()
plt.grid(True ,color='k')
plt.show()
```


![png](output_0_0.png)



```python
courses=['biology','physics','math','chemistry']
courses.insert(0,'history')
courses.append('A.I')
courses.remove('physics')
for index,course in enumerate (courses, start=1):
 print(index,course)

```

    1 history
    2 biology
    3 math
    4 chemistry
    5 A.I
    


```python
enter_details=input('enter your name:')
print('oopsy i thought your name as mary haha')
enter_hobbies=input('enter your hobbies:')
print('thats a beautiful one there')
first_num=int(input('Enter a number:'))
print('amazing now enter another number')
second_num=int(input('enter a second number:'))
print('your sum is now')
print(first_num + second_num)
print('goobye stranger!')

```


```python

```
