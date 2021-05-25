# 函数的返回值
## break,continue,return 的区别
- `break`：结束当前的循环体（如`for`、`while`）
- `continue`：跳出本次循环，继续执行下次循环（如`for`、`while`）
- `return`：不仅可以退出循环，还能够返回`return`语句中的值，同时还可以结束当前函数体内的代码
# 函数的两种声明方式
## 利用函数关键字自定义函数（命名函数）
```javascript
function fn(){

}
fn();
```
## 函数表达式（匿名函数）
**var 变量名 = function() {};**
```javascript
var fun = function(arg) {
  console.log('')
}
fun('argument');
```
- fun是变量名，不是函数名
- 函数表达式声明方式跟声明变量差不多，只不过变量里面存的是值，而函数表达式里面存的是函数
- 函数表达式也可以进行传递参数