# Github Actions 个人使用经验
## npm-bump 自动更新版本号后发布npm

使用方式如 `.github/workflows/npm-bump-release.yml`

会自动升级版本号，然后发布到 npm

![](./image/npm-bump.jpeg)

## 监听dev分支PR自动设置版本号
![](./image/dev-pr-add-comment.jpeg)

## pull-request-labels PR自动打标升级版本号发布npm

参考: [github-actions-npm-version-bump-using-labels-on-pr-merge](https://medium.com/@johnathanmiller/github-actions-npm-version-bump-using-labels-on-pr-merge-8c716a488a64)

## github 环境变量
[github 环境变量](https://docs.github.com/en/actions/learn-github-actions/contexts)