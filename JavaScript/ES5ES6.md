# 本章说明

 **ECMAScript**是一种由[Ecma国际](https://baike.baidu.com/item/Ecma国际)（前身为[欧洲计算机制造商协会](https://baike.baidu.com/item/欧洲计算机制造商协会/2052072)，European Computer Manufacturers Association）通过ECMA-262标准化的脚本[程序设计语言](https://baike.baidu.com/item/程序设计语言)。这种语言在[万维网](https://baike.baidu.com/item/万维网)上应用广泛，它往往被称为[JavaScript](https://baike.baidu.com/item/JavaScript)或[JScript](https://baike.baidu.com/item/JScript)，所以它可以理解为是JavaScript的一个标准,但实际上后两者是ECMA-262标准的实现和扩展。 [【百度百科】](https://baike.baidu.com/item/ECMAScript/1889420?fr=aladdin)

## ES5

 ES5通过对现有JavaScript方法添加语句和原生ECMAScript对象做合并实现标准化。ES5还引入了一个语法的严格变种，被称为”严格模式(strict mode) ， ES5总结来说，新的特性就是如下5点： 

1. 严格模式

2. 提供全局的JSON对象

   ```
   JSON.parse(text [, reviver])
   JSON.parse反序列化的方法接受文本（JSON格式）转化为JSON对象，其中第二个参数是一个回调函数，主要是用来过滤返回值。
   
   JSON.stringify(value [, replacer [, space]])
   value：js对象
   replacer：替换对象，可以是一个方法、对象或数组，将value按照替换规则展示。
   space：填充参数，可以是数字或字符串，将value按照参数进行格式化展示。
   方法说明：将value对象转换为指定格式的json文本
   ```

   

3. 附加对象--添加到Object上的构造器

   ```javascript
   Object.getPrototypeOf
   Object.getOwnPropertyDescriptor
   Object.getOwnPropertyNames    //几乎相同Object.keys但返回对象的所有属性名称（不只是可枚举的）
   Object.create    //创建一个新对象，其原型等于proto的值
   Object.defineProperty
   Object.defineProperties
   Object.seal     //密封对象可防止其他代码删除或更改任何对象属性的描述符，以及添加新属性
   Object.isSealed        //密封对象可防止其他代码删除或更改任何对象属性的描述符，以及添加新属性
   Object.freeze
   Object.preventExtensions //关闭可扩展性可能会阻止新属性添加到对象,锁定一个对象，防止属性增加。返回对象
   Object.isFrozen     //冻结物体几乎与密封物体相同，但是添加了不可修改的属性
   Object.isExtensible  //关闭可扩展性可能会阻止新属性添加到对象，确定对象当前可扩展性的一种方法，返回bool
   Object.keys     //返回表示对象的所有可枚举属性名称的字符串数组
   Object.hasOwnProperty  //判断是否拥有某个属性
   ```

4. 额外的数组——添加到Arrayprototype对象上

   ```
   Array.prototype.indexOf     //测试一个元素是否存在于一个集合中 Array.prototype.lastIndexOf     //类似indexOf，除了它从数组的末尾开始搜索元素
   Array.prototype.every    //集合中的所有项目是否满足指定的条件
   Array.prototype.some    //集合中的某些或所有项目是否满足指定的条件
   Array.prototype.forEach(function(item,index,Array)) 
   Array.prototype.map     //原始数组的转换或映射
   Array.prototype.filter  //过滤
   Array.prototype.reduce     //将一个数组减少为一个值 reduce(function (previous, current, index, array)，回调函数接受四个参数：上一个值，当前值，索引，以及数组本身
   Array.prototype.reduceRight  //将一个数组减少为一个值，工作方式与以下相同reduce，除了它从最后处理数组之外
   Array.isArray    //直接将方法写在了构造器上，判断数组
   ```

5.  Function.prototype.bind(thisArg [, arg1 [, arg2, …]])

    bind方法用于将函数体内的this绑定到某个对象，然后返回一个新函数 

## ES6

1. let const

   ​		ES6新增加let关键字，用来声明变量。用法类似var,但所声明的变量只在该代码块内有效。

   ​		const 声明的只是一个只读的变量，一旦声明，就不能改变。 const实际上保证的，并不是变量的值不得改动，而是变量指向的那个内存地址不得改动。对于简单类型的数据（数值、字符串、布尔值），值就保存在变量指向的那个内存地址，因此等同于常量。但对于复合类型的数据（主要是对象和数组），变量指向的内存地址，保存的只是一个指针，const只能保证这个指针是固定的，至于它指向的数据结构是不是可变的，就完全不能控制了。因此，将一个对象声明为常量必须非常小心。 

2. 解构赋值

    		ES6 允许按照一定模式，从数组和对象中提取值，对变量进行赋值，这被称为解构（Destructuring）。

   ```javascript
   /*基本*/
   let [a, b, c] = [1, 2, 3];
   // a = 1
   // b = 2
   // c = 3
   /*嵌套*/
   let [a, [[b], c]] = [1, [[2], 3]];
   // a = 1
   // b = 2
   // c = 3
   
   /*可忽略*/
   let [a, , b] = [1, 2, 3];
   // a = 1
   // b = 3
   
   /*不完全解构*/
   let [a = 1, b] = []; 
   // a = 1, b = undefined
   
   /*剩余运算*/
   let [a, ...b] = [1, 2, 3];
   //a = 1
   //b = [2, 3]
   
   /*对象结构*/
   let { foo, bar } = { foo: 'aaa', bar: 'bbb' };
   // foo = 'aaa'
   // bar = 'bbb'
    
   let { baz : foo } = { baz : 'ddd' };
   // foo = 'ddd'
   ```

   

3. 模板字面量 

   ​		它是允许嵌入表达式的字符串字面量。你可以使用多行字符串和字符串插值功能。它们在ES2015规范的先前版本中被称为“模板字符串” 。 模板字符串使用反引号 (` `) 来代替普通字符串中的用双引号和单引号。模板字符串可以包含特定语法（`${expression}`）的占位符。占位符中的表达式和周围的文本会一起传递给一个默认函数，该函数负责将所有的部分连接起来，如果一个模板字符串由表达式开头，则该字符串被称为带标签的模板字符串，该表达式通常是一个函数，它会在模板字符串处理后被调用，在输出最终结果前，你都可以通过该函数来对模板字符串进行操作处理。在模版字符串内使用反引号（`）时，需要在它前面加转义符（\）。 

   ```javascript
   
   ```

   

4. 数组拓展

5. 箭头函数

6. 对象拓展