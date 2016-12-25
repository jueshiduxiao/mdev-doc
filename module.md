src/module

说明：

* 每一个module是一个vue component。

* 每一个module会以“module-”为前缀注册到全局。

* module只能是单实例。

* module被框架统一创建，且永不销毁，可以访问的生命周期为beforeMount, mounted, beforeUpdate, updated。

* module不可以使用props属性。

* 示例：

```html
<div class="doc">
    <module-header></module-header>
    <module-demo></module-demo>
    <module-footer></module-footer>
    <widget-demo></widget-demo>
</div>
```



