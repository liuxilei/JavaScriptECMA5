### 类型转换

- 显式类型转换
- 隐式类型转换(四则运算、判断语句、Native调用)

#### 显式类型转换

```javascript
//以下六个值的转化结果为false，其他的值全部为true
// undefined
// null
// -0
// +0
// NaN
// ''(空字符串)
console.log('undefined',Boolean(undefined)); //false

console.log('null',Boolean(null)); //false

console.log('0',Boolean(0)); //false

console.log('NaN',Boolean(NaN)); //false

console.log('',Boolean('')); //false
```