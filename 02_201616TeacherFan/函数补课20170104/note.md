## 函数补课
### 函数构成及步骤：
#### 一：函数的定义和调用；
- 定义三阶段：
    1. 开辟一个空间地址
    2. 把函数体内所有的JS代码作为字符串存在这个内存空间中；
    3. 把空间地址赋值给函数名；
- 函数调用2阶段：
    1. 当函数被调用的时候，会形成一个私有作用域；
    2. 把空间中的代码字符串作为JS代码来执行；
- 所以：只定义，不调用，函数不会执行；
### 二：闭包：当函数被调用的时候，会形成一个私有作用域，保护里面的变量不受外界的干扰，函数的这种保护机制，叫做闭包；
### 三：函数按照是否有名字，分为：有名函数+匿名函数
1. 有名字函数，就是一般我们的函数体；
2. 匿名函数：
    - 函数表达式
    - 自执行函数，自执行函数多种写法：
      - (function(){})();
      - ~function(){}();
      - +function(){}();
      - -function(){}();
### 四：参数--任意个参数求和；
    - arguments：函数自带的参数机制叫做arguments;可以拿到函数调用时传的实参；
    - 使用场景：当参数不确定的情况下；
### 五：返回值
    - 返回值会出现undefined有两种情况：
        1. 没有写return
        2. 写了return但没有赋值
    - 是否要返回值：“获取”需要返回值，“设置”不需要返回值；


