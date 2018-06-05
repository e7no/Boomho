## Badges

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/8320deaa80b8489f95fcedaae6df079d)](https://www.codacy.com/app/zhiyi/thinksns-plus?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=slimkit/thinksns-plus&amp;utm_campaign=Badge_Grade)
[![codecov](https://codecov.io/gh/slimkit/thinksns-plus/branch/master/graph/badge.svg)](https://codecov.io/gh/slimkit/thinksns-plus)
[![Style CI](https://styleci.io/repos/76627423/shield?branch=master)](https://styleci.io/repos/76627423)
[![Composer publish version](https://img.shields.io/packagist/v/zhiyicx/thinksns-plus.svg?style=flat-square)](https://packagist.org/packages/zhiyicx/thinksns-plus)
[![Composer publish preview version](https://img.shields.io/packagist/vpre/zhiyicx/thinksns-plus.svg?style=flat-square)](https://packagist.org/packages/zhiyicx/thinksns-plus)
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fslimkit%2Fthinksns-plus.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Fslimkit%2Fthinksns-plus?ref=badge_shield)

Travis CI: [![Travis CI Build Status](https://img.shields.io/travis/slimkit/thinksns-plus.svg?style=flat-square)](https://travis-ci.org/slimkit/thinksns-plus)

Circle CI: [![https://img.shields.io/circleci/project/github/slimkit/thinksns-plus.svg?style=flat-square](https://img.shields.io/travis/slimkit/thinksns-plus.svg?style=flat-square)](https://circleci.com/gh/slimkit/thinksns-plus)

## 特点

Plus 是基于 Laravel 所开发，它拥有下面的几个主要特点：

1. 跟随 Laravel 一同升级，但是我们放弃 LTS 版本，长期的框架不变，虽然会趋于稳定，但是 Plus 是一款长期规划维护的开源项目，随时升级框架以便我们可以尽情的使用新的技术和特性
2. 前后端分离，Plus 安装完成只拥有功能快的 REST 接口部分，可以利用接口开发任何形态的客户端
3. 后台管理面板采用 Vue.js 开发
4. 使用 PHP 7 严格模式，以数据类型来限制开发人员的不规范开发
5. 完全符合 PSR 规范，代码风格选择的是比 PSR-2 更加严格的规范
6. 完善的文档，是的！在开源社区中， 一个开源项目的文档很重要。

## 文档

你可以在我们的文档网站上看到所有文档 👉 [https://slimkit.github.io](https://slimkit.github.io)

它被分为以下几个部分：

- [快速开始 · 安装](https://slimkit.github.io/docs/server-getting-started-installation.html)
- [指南](https://slimkit.github.io/docs/server-guides-package.html)
- [REST API v2](https://slimkit.github.io/docs/api-v2-overview.html)

当然，有一些并不在网站上，而是在 Plus 代码仓库中：

- [贡献指南 & 贡献者感谢名单](https://github.com/slimkit/thinksns-plus/blob/master/.github/CONTRIBUTING.md)
- [行为守则](https://github.com/slimkit/thinksns-plus/blob/master/.github/CODE_OF_CONDUCT.md)

## 安装

安装 Plus 是一件非常简单的事情，但是你要先做到以下几点必须：

- PHP 版本必须大于 `7.1.3`
- 你已下载并安装过 `Composer`
- 你拥有一个 `MySQL` 或者 `PostgreSQL` 等数据库

下载程序：

```shell
composer create-project zhiyicx/thinksns-plus
cd thinksns-plus
```

> 现在，打开你的 `.env` 文件配置数据库等各类信息，然后执行后面的步骤！

生成数据表以及默认填充数据：

```shell
php artisan migrate --seed
```

软链公开磁盘并发布静态资产：

```shell
php artisan storage:link
php artisan vendor:publish --all
```

运行 Plus 程序：

```shell
php artisan serve
```

现在你可以访问 `http://127.0.0.1:8000` 查看你安装的 Plus 程序了，但是上述只是一份简单的安装，更加详细或者可以运行在
正式环境的安装指南请参阅 👉 [安装指南](https://slimkit.github.io/docs/server-getting-started-installation.html)

<<<<<<< HEAD
=======
## 交流 & 支持

你可以申请加入官方 QQ 群进行交流，群号 `651240785`。

>>>>>>> thinksns/master
## 贡献

这个仓库的贡献者并不代表只是 Plus 的贡献者，我们也会把 Laravel 的贡献者加入感谢名单，因为他们为 Laravel 所做出的贡献，也使得 Plus 项目更加强大。

感谢所有为 Plus 贡献的人！
<a href="https://github.com/slimkit/thinksns-plus/graphs/contributors"><img src="https://opencollective.com/thinksns-plus/contributors.svg?width=890" /></a>

### [行为守则](https://github.com/slimkit/thinksns-plus/blob/master/.github/CODE_OF_CONDUCT.md)

我们按照开源项目社区的建议，为 Plus 提供了我们期望参与者遵守的行为准则，请 [阅读准则](https://github.com/slimkit/thinksns-plus/blob/master/.github/CODE_OF_CONDUCT.md) 全文，以便了解哪些行为是我们不会容忍的。

### [贡献指南](https://github.com/slimkit/thinksns-plus/blob/master/.github/CONTRIBUTING.md)

阅读我们的 [贡献指南](https://github.com/slimkit/thinksns-plus/blob/master/.github/CONTRIBUTING.md)，了解我们的开发过程，
如题提出错误修正或者建议，我们在贡献指南中包含了所有的贡献者名单。


## 优秀项目推荐

- [PHP CORS](https://github.com/medz/cors) 专为 PHP 开发的“跨域资源共享”中间件，快速解决 PHP 设置跨域问题
- [Notadd](https://github.com/notadd/notadd) 基于 Laravel 的下一代开发框架

## License

ThinkSNS Plus 代码遵循 Apache 2.0 许可证发布，请参阅完整的 [许可证文本](https://github.com/slimkit/thinksns-plus/blob/master/LICENSE)

[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fslimkit%2Fthinksns-plus.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2Fslimkit%2Fthinksns-plus?ref=badge_large)
