# Front-End-Interview
> 前端面试问题总结

### Html

- doctype

### Css

- 清除浮动

- 伪类, 伪元素

- 元素居中（垂直居中、水平居中）

### JavaScript

- this, arguments

- call, apply, bind

- 事件流

- 自定义事件

- 数组去重与降维

- 下列函数执行结果
```js
function test() {
  var a = 0;
  return function () {
    console.log(++a);
  }
}

var m = test();
var n = test();

m();
m();
n();
```
```js
var a = [];
var A = new Function;

A.prototype = [];

var aa = new A();
aa.push(1)

console.log(aa.length);
console.log(a.length);
```
```js
var foo = 1;
function main() {
  console.log(foo);
  var foo = 2;
  console.log(this.foo);
  this.foo = 3;
}
main();
new main();
```
### Node.js

- express 中间件

### jQuery

- jQuery 整体架构

- jQuery 插件机制

- jQuery.extend

### Vue.js

- Vue 实例生命周期

- Vue生命周期钩子

- Vue如何实现watch

### Angular

- Angular 2 相较于Angular 1 有哪些变化

- TypeScript

### React

- React 组件生命周期


