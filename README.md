## 笔记
## 使用VuePress搭建github在线blog
- 创建一个远程仓库 whitebear_ts_study
- 修改docs/.vuepress/config.js: base: '/whitebear_ts_study/'
- 打包文档: npm run doc:build
- 将项目推送到github
  - git init
  - git add .
  - git commit -m "init"
  - git push origin master
- 发布文档: npm run doc:deploy
- 访问在线文档:  [1. 初识 TypeScript | TypeScript 入门 (yuanbo-wang.github.io)](https://yuanbo-wang.github.io/whitebear_ts_study/chapter1/01_初识TS.html)

