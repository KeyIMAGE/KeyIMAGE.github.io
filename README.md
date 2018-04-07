## 2018.04.07   第一次记录
从 3 月 16 日开始给 KEY-IMAGE 攝影工作室做技术支持。

**基础工作**

创建 KEY-IMAGE 邮箱，在 GitHub 上注册并创建同名仓库，设置 GitHub Pages，测试 GitHub Pages 正常运行。

**构思**

侧重选择适用于摄影师展示作品，重图片轻文字，以简单直观为主要基调，减少按钮及链接跳转，删减多余文字，适当留白，摄影师简介和联系方式也用最直观的表达，想要用单页完成所有展示及功能，最后筛选保留下了 5 个模板，进入 2 次筛选。

我最喜欢的一个模板：左边展示页右边标题-简介-列表页-页脚信息。
![](https://raw.githubusercontent.com/KeyIMAGE/photo/master/Lens%E6%A8%A1%E6%9D%BF%E5%9B%BE.png)

**工作开始**

模板选定后开始在模板上工作，3 月 17 日就完成第一版第一次，并发布到线上，桌面端移动端全部正常运行。

之后忙于看书复习刷题考试，无暇顾忌，考试完后立马开始接着做网页。

4 月 1 日完成第一版第二次。修改了上一次图片放大后失真的问题，重新调整了展示页和列表页图片大小的比例。
![](https://raw.githubusercontent.com/KeyIMAGE/photo/master/Len%E6%A8%A1%E6%9D%BF%E7%AC%AC%E4%B8%80%E7%89%88%E7%AC%AC%E4%BA%8C%E6%AC%A1.jpg)


4 月 2 日的凌晨上传完毕要展示的作品图片。*万万没想到的是 18 个小时后全部推倒重做。*


![](https://raw.githubusercontent.com/KeyIMAGE/photo/master/Len%E6%A8%A1%E6%9D%BF%E7%AC%AC%E4%B8%80%E7%89%88%E7%AC%AC%E4%B8%89%E6%AC%A1.jpg)

第一版最大的问题就是无法分类，列表页的所有图片杂乱无章的显示，所以我只能每个大类上传一张代表图片，例如：人物类、静物类和风景类等。
当我在思考要怎样解决分类问题，单页肯定完成不了这个功能，必须在主页上加上链接跳转到子页面，主页上做分类，一个分类一个链接，链接跳转到子页面，子页面包含该分类下的所有作品图片。这样既能保证主页面的简洁直观又能保证子页面里的图片的无损放置，子页面里的图片竖排放置彻底解决横向图片和纵向图片的布局问题。

**这一设想与最初的单页面完成所有展示及功能的想法相悖。没啥可惜的，全部推倒重做。**

4 月 2 日晚上，全新第二版出炉上线。

4 月 4 日给网页加上了「不蒜子」计数，主页统计访客人数，子页统计查看次数。

4 月 7 日上传摄影师新拍摄的宣传样片。

![](https://raw.githubusercontent.com/KeyIMAGE/photo/master/%E7%AC%AC%E4%BA%8C%E7%89%88.jpg)

**发现问题，又开始思考**

因为此网页用于上传摄影作品，几乎不会对图片进行任何压缩，为保证浏览的全是高清无损大图。
对于 GitHub Pages 的加载是不小的压力，加载时间过长会非常影响用户体验。
思考 2 个解决方案：
1. 使用 Yelp 压缩工具，一个号称只压缩图片 30%的神器。
2. 在国内（例如在 Coding 上）建一个图片仓库，缓解图片加载压力。
测试 2 个方案的加载速度，择优选取，实现页面优化。

**小结**

从 3 月 16 日到 4 月 7 日，不断重复「发现问题」-「思考」-「解决问题」的过程。
作为一个程序人，写出让自己满意的作品是一件很骄傲的事。
