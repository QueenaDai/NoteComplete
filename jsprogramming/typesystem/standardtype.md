# 标准类型
* 原始类型、引用类型<br />
```
/*
BEGIN   FOR EACH
    类型说明
    出现场景
    类型转换
END
*/
```
![](241.PNG)<br />
![](2411.PNG)<br />
![](2412.PNG)<br />
<br />
![](2413.PNG)<br /><br />
Note: <br />
**出现场景:**<br />
* 已声明未赋值的变量：a显示声明后未赋值   b隐式声明后未赋值<br />
![](24131.PNG)<br />
* 获取对象不存在的属性<br />
![](24132.PNG)
* 无返回值的函数的执行结果<br />
![](24133.PNG)
* 函数未传入的参数<br />
![](24134.PNG)<br />
**案例：**
![](24135.PNG)![](24136.PNG)<br />
![](24137.PNG)![](24138.PNG)<br />
![](24139.PNG)![](241310.PNG)<br />
<br />
![](2414.PNG)<br />
![](2415.PNG)<br />
![](2416.PNG)<br />
![](2417.PNG)<br />
![](2418.PNG)<br />
<br />
**类型转换总结**<br />

| type | Value | Boolean | Number | String |
| -- | -- | -- | -- | -- |
| **Undefined** | undefined | false | **NaN** | "undefined" |
| **Null** | null | false | 0 | "null" |
| **Boolean** | true |  | 1 | **"null"** |
|  | true |  | 0 | "false" |
| **String** | "" | false | 0 |  |
|  | "123" | true | 123 |  |
|  | "1a" | true | **NaN** |  |
| **Number** | 0 | false |  | "0" |
|  | 1 | true |  | "1" |
|  | -1 | true |  | "-1" |
|  | Infinity | true |  | "Infinity" |
|  | NaN | **false** |  | **"NaN"** |
| **Object** | {} | **true** | **NaN** | **"[object Object]"** |

![](2419.png)<br />
![](24191.png)<br />
![](24193.png)<br />
