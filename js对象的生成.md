  https://segmentfault.com/a/1190000000602050
  
  https://segmentfault.com/q/1010000004596650
  
  https://www.zhihu.com/question/34183746/answer/58068402

## 生成对象的方法
    1.使用new关键字创建 
    2.字面量创建 
    3.Object.create
    4.使用工厂模式 
    5.使用构造函数 
    6.原型对象模式 
    7.原型对象和构造函数一起使用，各自属性和相同的方法

## 构造函数和工厂模式的区别（new关键字的作用）
     JS里的构造函数就是一个用来构造对象的普通函数，和JAVA不同
    你要知道，通过new 来调用函数，会自动执行下面操作
    1.创建一个全新的对象
    2.这个对象会被执行[[prototype]]连接原型
    3.函数调用中的this会绑定到新对象
    4.如果函数没有返回其他对象，那么new 构造就会自动返回这个新对象
 
##prototype 和 __proto__
