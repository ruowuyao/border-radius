# border-radius
## 一、border-radius设置值
w3school中border-radius的语法介绍:1-4 length|% / 1-4 length|%;  
**注释1**：按此顺序设置每个 radii 的四个值。如果省略 bottom-left，则与 top-right 相同。如果省略 bottom-right，则与 top-left 相同。如果省略 top-right，则与 top-left 相同。  
**注释2**:length|%:而已用length(em)定义圆角的形状,也可以用%百分比定义圆角的形状。  
1. border-radius: 2em 1em 4em / 0.5em 3em;
等价于:  
* border-top-left-radius: 2em 0.5em;
* border-top-right-radius: 1em 3em;
* border-bottom-right-radius: 4em 0.5em;
* border-bottom-left-radius: 1em 3em;  
### 我们先来看一下如果非4个值的情况下,值分别为多少:
1. 1     2     3     4  
  上     右    下    左
2. 1     2     3      
  上     左右  下
3.1      2  
  上下   左右
4.1  
  上下左右
因此,2em     1em     4em    /     0.5em     3em    
x轴长度:2em(上)  1em(右) 4em(下) 1em(左)  
y轴长度:0.5em(上)  3em(右) 0.5em(下) 3em(左)  
所以上方等价成立!
![border-radius](http://thumbnail0.baidupcs.com/thumbnail/5fb3a890179214ab6669ab3f44a4856b?fid=4130315690-250528-434582210467632&time=1461225600&rt=sh&sign=FDTAER-DCb740ccc5511e5e8fedcff06b081203-3XBg8lRY2bNWkPC7vy%2FWwPUt2NI%3D&expires=8h&chkv=0&chkbd=0&chkpc=&dp-logid=2589960133312319395&dp-callid=0&size=c710_u400&quality=100)


