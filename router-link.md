`<router-link>` 组件支持用户在具有路由功能的应用中（点击）导航。

### Props

* href

  类型: string \| Location

  required

  表示目标路由的链接。当被点击后，内部会立刻把 to 的值传到 memory-router.pushState\(\)。

```html
<!-- 字符串 -->
<router-link href="home">Home</router-link>
<!-- 渲染结果 -->
<a href="home">Home</a>

<!-- 使用 v-bind 的 JS 表达式 -->
<router-link v-bind:href="'home'">Home</router-link>

<!-- 不写 v-bind 也可以，就像绑定别的属性一样 -->
<router-link :href="'home'">Home</router-link>
```



