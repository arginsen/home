

# 项目

[h5主页](https://www.lixupeng.cn)+[博客](https://lixupeng.cn/blog)构建

## 主页说明

`arginsen.github.io`项目作为个人自定义网站,地址https://lixupeng.cn

托管在GitHub，主页选自[数学家](https://zhwangart.github.io/)同学

其下项目作为主站的分支：`arginsen.github.io/home/`

以此使**GitHub pages**托管我的主页和下支的博客

**GitHub pages**上的[h5主页](https://lixupeng.cn/home)作为个人的h5主页测试页,同时托管在腾讯开发平台[h5主页](https://www.lixupeng.cn)

由于个人网站未能备案，所以不能启用腾讯云/七牛云CDN加速

试用**AWS**的**cloudfront**网站加速，但回源经常失败

>将`arginsen.github.io`作为回源域名，将`www.arginsen.com`作为源域
开启**cloundfront**分配，生成`xxxxxxxx.cloudfront.net`
再在域名解析页将****www**二级域解析至`xxxxxxxx.cloudfront.net`
借此得以加速，但经常断掉，故取消


