# 跨站伪造请求CSRF

> 跨站请求伪造（英语：Cross-site request forgery）， 是一种挟制用户在当前已登录的Web应用程序上执行非本意的操作的攻击方法。

利用用户登录的身份，以用户的名义完成非法操作。

> 攻击者通过一些技术手段欺骗用户的浏览器去访问一个自己曾经认证过的网站并运行一些操作，由于浏览器曾经认证过，所以被访问的网站会认为是真正的用户操作而去运行。





防御

- token验证
- 检查Referer字段

# 代码注入Code injection



