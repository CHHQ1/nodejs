# 史上最简单的静态站点生成器 

这可能是史上最简单的静态站点生成器了,使用markdown作为源文件.

生成html静态站点,并且html是渲染过的,搜索引擎友好

[原始GitHub站点](https://github.com/jingtaiboke/simple-markdown-site)

## 只有3个文件夹
1. posts:存放markdown文件
2. template : 模板文件
3. public : html发布文件


## local调试(使用)方法:
```shell
git clone https://github.com/jingtaiboke/simple-markdown-site
cd simple-markdown-site
npm i
npm run build
```
用到的库：markdown-styles
npm run build,在本地看到效果

## 可以一键部署Deploy到Vercel
部署到vercel云端的话，是在云端执行这两条命令
```shell
npm i
npm run build
```

# 推荐几个类似的项目

https://docsify.js.org/

直接加载md文件,无渲染,搜索引擎不友好,至少百度不友好 demo


https://github.com/jingtaiboke/artless

同上 无渲染 demo


https://github.com/me1a/mini-book

有渲染,node构建,首页直接是个搜索框

