<!--
    需要填充的占位符：
    
    README.md
    
        {name}：文档中文名
        {nameEn}：文档英文名
        {urlEn}：文档原始链接
        {domain}：域名前缀
        {adminName}：负责人名称
        {adminUn}：负责人 Github 用户名
        {adminQq}：负责人 QQ
        {repo}：ApacheCN 的 Github 仓库名称
        {dockerName}：DockerHub 仓库名称
        {pypiName}：PYPI 包名称
        {npmName}：NPM 包名称
    
    CNAME
    
        {domain}：域名前缀

    index.html
    
        {name}：文档中文名
        {color}：显示颜色
        {repo}：ApacheCN 的 Github 仓库名称

    asset/docsify-flygon-footer.js
    
        {repo}：ApacheCN 的 Github 仓库名称
-->

# {name}

> 原文：[{nameEn}]({urlEn})
> 
> 协议：[CC BY-NC-SA 4.0](http://creativecommons.org/licenses/by-nc-sa/4.0/)
> 
> 阶段：机翻（1）
> 
> 趁着年轻生猛，我要再和生活死磕几年。要么我就毁灭，要么我就铸就辉煌。如果有一天，你发现我在平庸面前低了头，那么请向我开炮。--《在路上》

* [在线阅读](https://{domain}.flygon.net)
## 下载

### Docker

```
docker pull apachecn0/{dockerName}
docker run -tid -p <port>:80 apachecn0/{dockerName}
# 访问 http://localhost:{port} 查看文档
```

### NPM

```
npm install -g {npmName}
{npmName} <port>
# 访问 http://localhost:{port} 查看文档
```

## 赞助我

![](https://img-blog.csdnimg.cn/20200112005920729.png)
