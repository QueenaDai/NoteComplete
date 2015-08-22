# Note Complete

#2. javascript程序设计
##2.1 js介绍
        * js历史
        * 浏览器中的js       
        * js引入
##2.2 调试器
##2.3 基本语法(词法重点)
        变量标识符
        关键字和保留字
        大小写敏感
        严格模式
        注释     
##2.4 类型系统
        标准类型
            原始类型、引用类型
                /* BEGIN FOR EACH
                    类型说明
                    出现场景
                    类型转换
                */ END

        类型识别
        标准内置对象（13种）
            构造器对象
                /* BEGIN FOR EACH
                    构造器说明
                    构造器实例化对象方法
                    属性、方法
                    原型对象的属性、方法
                    实例对象的属性、方法
                */ END
  
                Object  
                    Object.create
                    Object.prototype.toString
                    Object.prototype.hasOwnProperty
                Boolean
                String
                    String.prototype.indexOf
                    String.prototype.replace
                    String.prototype.split
                Number
                    Number.prototype.toFixed
                Array
                    Array.prototype.splice
                    Array.prototype.forEach
                Function
                    自定义对象构造函数
                    Function.prototype.apply
                    Function.prototype.bind
                    子类构造器
                    函数调用
                    函数参数
                        arguments
                        值传递
                        函数重载
                RegExp
                    RegExp.prototype.test
                Date  
            普通对象
                /* BEGIN FOR EACH
                    说明
                    属性、方法
                */ END
        
                Math
                    Math.floor
                    Math.random
                JSON
                    JSON.stringify
                    JSON.parse
                全局对象
                    属性
                        NAN
                    方法
                        parseInt
                        eval
                    处理URI方法
                        encodedURIComponent
                    构造器属性
                    对象属性
##2.5 变量作用域
        作用域介绍
            静态作用域
            动态作用域
        js中变量作用域
            基础概念
                声明提前
            函数
            with、try-catch
            作用域链
        静态作用域的管理：词法环境
            组成
            初始化
            执行
            问题
##2.6 函数表达式与函数运算符
        表达式
            函数定义和函数表达式(带名称的函数表达式)
        运算符
            关系运算：==、===
            逻辑运算：！、&&、||
            运算符优先级
##2.7 语句
        条件控制语句  
        循环控制语句
            for-in
        异常处理语句
        with语句
##2.8 闭包
        原理
        闭包的应用
            保存变量现场
            封装
##2.9 面向对象
        面向对象的基本特征
        js面向对象
            constructor
                自定义构造器
                3种创建构造器的方式 
            this
                5种场景
                案例
            原型
            原型链
                属性查找
                属性修改
                属性删除
                tom.hasOwnProperty('job');
            原型继承案例
                Object.create();
            面向对象应用
                全局变量
                封装
                继承
                    原型继承
                    类继承
