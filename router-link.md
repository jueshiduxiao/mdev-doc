`<router-link>` 组件支持用户在具有路由功能的应用中（点击）导航。

### Props

* href

  类型: string \| Location

  required

  表示目标路由的链接。当被点击后，内部会立刻把 to 的值传到 memory-router.pushState\(\)。

```html
<!-- 字符串 -->
<router-link href="/home">Home</router-link>
```



