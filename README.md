#<center>玩转iOS开发：Aggregate脚本版本《模拟器与真机静态Framework合成教程》</center>

---
### 简介

> 之前我写了一个关于非**`Aggregate`**版本的[《模拟器与真机静态Framework合成教程》](http://www.jianshu.com/p/305c62fa9e2b), 但那个实在是太麻烦的, 所以我又出墙翻了一些歪果仁写的博客, 果然是世上无难事只怕有心人, 终于被我找到合适的**`Shell`**脚本了

---

###作者感言
> 为了写这篇文章, 我翻查了许多资料, 都没有找到详细点的可参考资料, 外国的文章就不用说了, 光是看鸡肠就头晕了, 所以我自己总结了一些经验, 整理了一番, 决定分享出来, 希望大家喜欢

> 最后:
> 如果你有更好的建议或者对这篇文章有不满的地方, 请联系我, 我会参考你们的意见再进行修改, 联系我时, 请备注**`Aggregate-Framework`** 如果觉得好的话, 希望大家也可以打赏一下~嘻嘻~祝大家学习愉快~谢谢~
>

<p align="right">Cain(罗家辉)</p>
<p align="right">zhebushimengfei@qq.com: 联系方式</p>
<p align="right">350116542: 腾讯QQ</p>

---
###详细文档

[《使用系统自带的UIActivityViewController和UIActivity进行内容分享》文档](https://github.com/CainRun/iOSDeveloperDocument/blob/master/%E7%8E%A9%E8%BD%ACiOS%E5%BC%80%E5%8F%91%EF%BC%9A%E3%80%8A%E4%BD%BF%E7%94%A8%E7%B3%BB%E7%BB%9F%E8%87%AA%E5%B8%A6%E7%9A%84UIActivityViewController%E5%92%8CUIActivity%E8%BF%9B%E8%A1%8C%E5%86%85%E5%AE%B9%E5%88%86%E4%BA%AB%E3%80%8B/%E7%8E%A9%E8%BD%ACiOS%E5%BC%80%E5%8F%91%EF%BC%9A%E3%80%8A%E4%BD%BF%E7%94%A8%E7%B3%BB%E7%BB%9F%E8%87%AA%E5%B8%A6%E7%9A%84UIActivityViewController%E5%92%8CUIActivity%E8%BF%9B%E8%A1%8C%E5%86%85%E5%AE%B9%E5%88%86%E4%BA%AB%E3%80%8B/%E7%8E%A9%E8%BD%ACiOS%E5%BC%80%E5%8F%91%EF%BC%9A%E3%80%8A%E4%BD%BF%E7%94%A8%E7%B3%BB%E7%BB%9F%E8%87%AA%E5%B8%A6%E7%9A%84UIActivityViewController%E5%92%8CUIActivity%E8%BF%9B%E8%A1%8C%E5%86%85%E5%AE%B9%E5%88%86%E4%BA%AB%E3%80%8B.md)
