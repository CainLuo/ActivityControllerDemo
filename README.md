# <center>玩转iOS开发：《使用系统自带的UIActivityViewController和UIActivity进行内容分享》</center>

---
###简介
> 这段时间有很多朋友都问我关于怎么去集成**`ShareSDK`**或者**`友盟社会化分享SDK`**的问题, 其实我想说, **`Apple`**一开始就提供了一个类, 供我们去使用分享了, 在**`iOS 6`**之后更加增强了这个类, 使我们不再需要集成第三方的, 而且还支持自定义分享的**`item`**.

---
###作者感言
> 在我写这篇文章的时候, 虽然国内有一堆文章介绍**`UIActivityViewController`**和**`UIActivity`**, 但都是零零散散的, 哪怕我翻墙出去看**`YouTube`**, 或者是著名的**[黑胡子博客](http://nshipster.com/uiactivityviewcontroller/)**, 都没有详细的讲解怎么去自定义所需的**`UIActivity`**, 最后基本上翻遍了谷歌, 才找到了所需的.
> 
> **最后:**
> 如果你有更好的建议或者对这篇文章有不满的地方, 请联系我, 我会参考你们的意见再进行修改, 联系我时, 请备注**`UIActivityViewController`** 如果觉得好的话, 希望大家也可以打赏一下~嘻嘻~祝大家学习愉快~谢谢~
>

<p align="right">Cain(罗家辉)</p>
<p align="right">zhebushimengfei@qq.com: 联系方式</p>
<p align="right">350116542: 腾讯QQ</p>

---
###详细文档

[《使用系统自带的UIActivityViewController和UIActivity进行内容分享》文档](https://github.com/CainRun/iOSDeveloperDocument/blob/master/%E7%8E%A9%E8%BD%ACiOS%E5%BC%80%E5%8F%91%EF%BC%9A%E3%80%8A%E4%BD%BF%E7%94%A8%E7%B3%BB%E7%BB%9F%E8%87%AA%E5%B8%A6%E7%9A%84UIActivityViewController%E5%92%8CUIActivity%E8%BF%9B%E8%A1%8C%E5%86%85%E5%AE%B9%E5%88%86%E4%BA%AB%E3%80%8B/%E7%8E%A9%E8%BD%ACiOS%E5%BC%80%E5%8F%91%EF%BC%9A%E3%80%8A%E4%BD%BF%E7%94%A8%E7%B3%BB%E7%BB%9F%E8%87%AA%E5%B8%A6%E7%9A%84UIActivityViewController%E5%92%8CUIActivity%E8%BF%9B%E8%A1%8C%E5%86%85%E5%AE%B9%E5%88%86%E4%BA%AB%E3%80%8B/%E7%8E%A9%E8%BD%ACiOS%E5%BC%80%E5%8F%91%EF%BC%9A%E3%80%8A%E4%BD%BF%E7%94%A8%E7%B3%BB%E7%BB%9F%E8%87%AA%E5%B8%A6%E7%9A%84UIActivityViewController%E5%92%8CUIActivity%E8%BF%9B%E8%A1%8C%E5%86%85%E5%AE%B9%E5%88%86%E4%BA%AB%E3%80%8B.md)
