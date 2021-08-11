# dlproxy
<div style="text-align: center;width: 100px;margin: auto;">
<img src="https://dlproxy.tes286.top/logo.svg" style=""/>
</div>
这是一个万用的下载加速器,使用cloudflare部署,详见github.com/TES286/dlproxy

借鉴: [gh-proxy](https://github.com/hunshcn/gh-proxy)

[捐助](https://dlproxy.tes286.top/Donate.html)

# 使用方法
直接拼接源地址到站点地址之后即可,如下:

> 假设需要下载 https://example.com/example.file 站点地址是 https://proxy.0123465789.workers.dev/ 则直接访问下面的链接即可
>
> > 一定要带上http或https头!!!
>
> https://proxy.0123456789.workers.dev/https://example.com/example.file

# 示例站 

1: proxy.0123456789.workers.dev

2: proxy.123456abc.workers.dev

3: proxy.tes286.workers.dev (不建议)

同时欢迎大家将自己的节点共享出来,可以在issue界面联系我

# 自行搭建

注册一个[cloudflare](https://dash.cloudflare.com/)账户,并转到[workers](https://workers.cloudflare.com),验证邮箱,随便填写一个子域名,就可以创建workers了,内容就是[index.js](https://github.com/TES286/dl_proxy/raw/master/index.js) [备用](https://proxy.0123465789.workers.dev/https://github.com/TES286/dl_proxy/raw/master/index.js)

> 如果让你添加域名,别管,另外,可以选择简体中文的语言的
>
> 免费版每天限制10000次,个人使用大多的,要是不够多开几个号,或者买付费

# 捐助

[按这里](https://dlproxy.tes286.top/Donate.html)
