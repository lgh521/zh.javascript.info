importance: 5

---

# 作为方法的绑定函数

输出将会是什么？

```js
function f() {
  alert( this ); // ?
}

let user = {
  g: f.bind(null)
};

user.g();
```

