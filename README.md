# Vue3-DiDa

使用 Vue3 来实现滴答清单的功能

> 展示复杂前端项目应该如何测试

## why

做这个项目的目的主要是为了展示前端项目应该如何测试

我是一名前端测试布道者，在布道测试的时候听到最多的一句话就是： 测试很好 但是业务代码不适合/没法写

同时很多的测试教程资料也都是拿比较简单的 demo 来举例，和真实的业务场景不匹配 复杂性不够

所以我决定构建一个真实且偏复杂的前端项目为其加上对应的测试 展示业务代码应该如何测试

争取为推动前端社区测试方向贡献自己的力量

> 按照现在的互联网发展趋势来看已经到了"降本增效"的时代
程序员如何保证自己的代码质量以及提高工作效率将会成为重点问题
而测试就是这个问题的解

## Features

集成了以下技术栈

- [x] vite
- [x] vue3
- [x] typescript
- [x] vitest
- [x] vue-router
- [x] pinia(vuex5)
- [x] naive-ui
- [x] cypress
- [x] cypress-component-test
- [x] alias
- [x] ci && cd
- [x] unocss (更好用的 tailwind-css)
- [x] git hooks (lint-stage + commit-lint)
- [x] eslint 校验
- [ ] lint + eslint + prettier
- [ ] axios

## 安装

执行下面的命令即可

```bash
pnpm bootstrap
```

执行这个命令安装依赖的话 会跳过 cypress 的安装
> 因为有很多同学反馈在安装 cypress 的时候超时

## 代码贡献指南

你需要安装 Node.js 16+ 版本和 PNPM 7+ 版本。

推荐使用 [ corepack ](https://nodejs.org/api/corepack.html) ，这样的话可以基于项目配置的包管理器版本来安装依赖。

### 1. 说明

- 一个 PR 只处理一件事，不要把无关代码提交上来，这样最好 Review 以及 Merged
- Issue 以 PR 为准，留言不算。
- PR 的标题要使用英文
- 当发生多个 PR 同时解决一个 Issue 的时候，会随机合并，注意没合并你的 PR 不代表你的实现不好，不要灰心，不要抱怨。你要做的是看看其他 PR 有没有可以学习的地方和可以优化的地方，友好的指出来，当你实现一遍后其实就已经学到很多了。

## 如何参与进来

项目要开发的功能直接参考滴答清单来就可以

我会把任务拆分放到 issues 列表里面

如果你想参与进来的话 可以直接去翻看 issues

当然你也可以主动发现问题/需求

比如说你发现了一个 bug ，然后就可以先去创建一个 issue 解决完成之后在发一个 pr 过来即可

在比如你发现一个滴答清单的功能 在项目的 issues 里面并没有被说明，那么你也可以创建一个 issue 然后实现完成后发一个 pr 过来

## 参与进来可以收获到什么

1. 这个项目使用到的技术栈全部都是社区里面最新的，可以让你学到很多新技术
2. 比普通前端项目复杂度要高，可以让你接触到更复杂的业务场景
3. 可以感受到测试的魅力，如何写测试以及如何使用测试来提高项目的质量
4. 每一个 pr 我都会去 review ，你可以在 review 的过程收获很多编程上的技巧
5. 暂时想不到了  想到了在说 - -#  

总之参与进来会对你技术提高有很大的帮助，而且开源合作方式就比较的自由，有时间了就来领个任务做做涨涨经验值 没时间了就该忙啥忙啥去
