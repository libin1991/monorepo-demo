[Monorepo实战](https://juejin.cn/post/6866748110644822023)

[从0开始使用pnpm构建一个Monorepo方式管理的demo](https://juejin.cn/post/7115058575801581605)

- utils安装jquery
```
lerna add jquery --scope utils 
```
- components安装utils
```
lerna add utils --scope components
```