TypeScript Same Namespace in Multiple Files Demo
===========================

typescript中的`namespace`以前被称为"internal modules"。

可以让我们把处于同一命名空间下的定义和内容分散在多个文件中，在某些情况下方便使用，但不是很推荐，因为很多情况下可以使用module或者其它更简单的方式处理。

在定义一个namespace时，不要使用`export`，这样才可以在某一个文件中通过`/// <reference...`来引用多个拥有同名namespace的文件

```
npm install
npm run demo
```
