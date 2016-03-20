# Google Pipe

--------------

Google pipe 是基于ASP.Net Core 1.0开发的谷歌反向代理网站。

您可以在Linux、Windows、Mac上部署这个网站系统，但前提是能够访问到www.google.com，这样就可以让其他用户通过您的网站访问Google了。

部署时，需要修改Startup.cs中app.UseReverseProxy中第二个参数，即域名部分。请在解析列表中使用泛解析，即`*.yourdomain.postfix`。

这个GitHub仓库中存储的是源代码，不是发布版本，因此如果您欲直接使用源代码部署，可能需要安装相应的环境，如dnvm、dnx、dnu等必要软件，您可以参阅微软官方网站获得更多信息：[http://docs.asp.net](http://docs.asp.net)

演示网址：[http://www.gglink.pw](http://www.gglink.pw)