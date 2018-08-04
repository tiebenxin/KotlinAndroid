# VIPVideo
基于组件化 + MVP + Retrofit + RxKotlin + Dagger2实现的一款用Kotlin语言实现的影视类应用。

## 模块化结构图

![](/screenshot/模块化.png)

>Common为公共库，主要包含一些基类和常用的工具类，Provider依赖于Common，是业务模块真正依赖的库。业务模块包括：Home，Music，User，Player。
