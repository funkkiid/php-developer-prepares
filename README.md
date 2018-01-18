# PHP 开发者实践
PHP Developer Prepares

> 本开源书 forked from [PHP 开发者实践](https://github.com/zacao/php-developer-prepares)，作者为 [zacao](https://github.com/zacao)，欢迎大家 star 原作者的 [repo](https://github.com/zacao/php-developer-prepares)，以便获得最新更新，谢谢！

坚持了 5 年的创业项目决定结束了（行业垂直搜索方向，理想很美好、现实很骨感），作为没混好的草根站长 & 没被风吹起来的小互联网公司技术合伙人，个人基本见证了这几年 PHP 环境的发展（当然主要归功于互联网创业风潮大爆发），感受了一些 PHP 团队和从业者的现状；同时，我们自身在 PHP 研发团队组建过程中也遇到了不少问题，一直想把创业过程中遇到的这些团队实践相关问题整理、总结一下，目前只是个初始版本，欢迎大家拍砖 & 加入！

技术的发展日新月异，我会持续维护、跟进这个项目，欢迎各位有兴趣的朋友 [提交建议、问题 - Issue](https://github.com/zacao/php-developer-prepares/issues) 或 [参与贡献、分享 - Pull Request](https://github.com/zacao/php-developer-prepares/pulls)。

* 本项目排版遵循 [文案排版指北](https://github.com/sparanoid/chinese-copywriting-guidelines) 和 [Stack Overflow Markdown](http://stackoverflow.com/editing-help) 规范
* 本项目使用了 GitBook 并已发布在 [GitBook.com](http://ryancao.gitbooks.io/php-developer-prepares/content/) 上，关于如何使用 Gitbook 编写、生成、发布一本在线图书，请移步 [GitBook Documentation](http://help.gitbook.com/) 或 [Gitbook 使用入门 - 中文](http://wanqingwong.com/gitbook-zh)

    > * GitBook.com 是一个很优秀的社区，上面有很多优秀作者自出版自己的著作，就好像 [Leanpub](https://leanpub.com/)
    > * Gitbook 是 GitBook.com 提供的一个开源的基于 Node.js 开发的配套工具 - [Github 地址](https://github.com/GitbookIO/gitbook)


* 开发过程中遇到的绝大多数问题实际上都可以通过搜索引擎找到，关于搜索引擎使用技巧，请参考  [如何用好 Google 等搜索引擎？](http://www.zhihu.com/question/20161362)
* 开发过程中遇到问题在论坛、社区中提问是很常见的情况，如何让他人快速理解你的问题、同时自己如何在提问中学习成长，推荐阅读： [How To Ask Questions The Smart Way](http://www.catb.org/~esr/faqs/smart-questions.html)，[提问的智慧 - 中文版](http://doc.zengrong.net/smart-questions/cn.html) 或 [提问的智慧 - 图片版](./assets/smart-questions-cn.jpg)

    > 「《提问的智慧》就是一个敲门砖，它把黑客间的礼仪和准则明白地写下来。它会让你了解到一个事实，为什么那些看起来很牛的人几乎从不提问，似乎他们一进入这个行业就是牛人了。不是的，他们也有问题，但是通常在提问之前就自己解决了；不是因为他们本来就懂得怎么解决，而是解决问题的经历让他们成为牛人；最终，你只会看到网络上多了一篇文章：关于解决XXX问题的方案。」-- Rei

* 因为关于如何使用 PHP 语言本身相关资料已有很多，本文将尽量不涉及 PHP 语言本身、且优先引用已有资料，主要围绕关心 PHP 项目开发技巧和具体实践，通过相关工具和经验的分享，使大家在项目中更好的使用 PHP 技术。

----------

## 在线阅读

> 重要说明：正在持续修改之中，大部分章节都没有写完，正式发布还需要一段时间，所有内容随时可能发生变动。

* http://ryancao.gitbooks.io/php-developer-prepares/content/


## 如何参与

本项目在 Github 上维护，欢迎参与：[https://github.com/zacao/php-developer-prepares](https://github.com/zacao/php-developer-prepares)。

* 在 GitHub 上把本项目 `fork` 到自己的仓库，如 `<your-username>/php-developer-prepares`，然后 `clone` 到本地，并设置用户信息。
```
$ git clone git@github.com:<your-username>/php-developer-prepares.git
$ cd php-developer-prepares
$ git config user.name "yourname"
$ git config user.email "your email"
```
* 修改代码后提交，并推送到自己的仓库。
```
$ #do some change on the content
$ git commit -am "Fix issue #1: change helo to hello"
$ git push
```
* 在 GitHub 网站上提交 pull request。
* 定期使用项目仓库内容更新自己仓库内容。
```
$ git remote add upstream https://github.com/zacao/php-developer-prepares
$ git fetch upstream
$ git checkout master
$ git rebase upstream/master
$ git push -f origin master
```


## 授权许可

本文采用创意共享 [「署名-非商业性使用」](http://creativecommons.org/licenses/by-nc-nd/3.0/deed.zh) 许可证（Creative Commons Attribution-NonCommercial license）。所有内容不仅可以免费阅读，还可以自由使用（比如转载），只需遵守两个条件：

* **署名**：必须保留原作者的署名。

* **非商业性使用**：除非得到正式许可，否则不得用于商业目的。
