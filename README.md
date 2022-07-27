- [Monorepo实战](https://juejin.cn/post/6866748110644822023)
- [使用lerna管理monorepo及发npm包实战教程](https://zhuanlan.zhihu.com/p/404166248)
- [从0开始使用pnpm构建一个Monorepo方式管理的demo](https://juejin.cn/post/7115058575801581605)
- [一文学会用Lerna管理多个npm包](https://blog.csdn.net/uikoo9/article/details/124190634)



- utils安装jquery
```
lerna add jquery --scope utils 
```
- components安装utils
```
lerna add utils --scope components
```

- 发布
```
lerna publish
```
