---
title: 创建新项目和设置代码源的目的
taxonomy:
    category:
        - docs
process:
    twig: true
---

<!--
与代码库建立对接，实现代码和持续集成（CI）、容器镜像构建过程的自动化联动

介绍后台的技术：代码库对接采用 OAuth，触发采用 Webhook

强调容器事未来软件的交付件，通过关联代码仓库，实现代码迭代和交付件的同步更新，保证项目随时都有可供交付的实体，而不是一堆需要人工配置才能运行起来的代码

这一篇更多是讲我们的设计理念，不需要涉及到 DaoCloud 产品的细节，篇幅 500 字以内即可，可以适当引用诸如等说教性内容：http://12factor.net/zh_cn/

强调关联代码库，自动构建是持续交付的前提，有些人（我们的一些竞争对手）建议用户采用手动构建，或者开发命令行工具在本地帮助用户做构建然后上传到容器云，这些都是不规范的做法。

-->