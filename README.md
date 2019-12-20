# About My Cli

该脚手架是基于 `vuepress` 框架搭建，然后使用了 `vuepress-theme-reco-cli` 主题，由于该主题有些我不喜欢的地方，我重新做了简单封装，做成了自己的博客项目的脚手架，欢迎交流相互学习。

## Version

1.0.3

## Experience

```sh

# show version
npx cym-blog -v

# create
npx cym-blog init my-blog

# or
npm install -g cym-blog
cym-blog init my-blog

# install
cd my-blog
npm install

# run
npm start

# build
npm run build
```

**if yarn**

```bash

# create
npx my-blog init my-blog

# or
yarn global add my-blog
cym-blog init my-blog

# install
cd my-blog
yarn install

# run
yarn start

# build
yarn build
```

## test

非脚手架功能，测试使用

```sh
  # 测试init命令
  npm run test:init
  # 测试下载功能
  npm run test:download
  # 测试全部功能
  npm run test:all
  # 删除测试所下载的文件
  npm run rm:all-test
```

## Blog

[About me](http://chengyuming.cn/)
