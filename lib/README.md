当数据未加载完时出现闪烁的解决方法：[`v-cloak`](vuejs.org/api/#v-cloak)

```CSS
[v-cloak] {
  display: none;
}
```

```HTML
<div v-cloak>
  {{ message }}
</div>
```
