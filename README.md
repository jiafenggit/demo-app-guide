#基于 Swipe 前端框架实现的 App 引导页

绝大多数 App 都会有自己的引导页、广告页等。
引导页的实现创意可以说是千变万化，但实际实现却大同小异。

##这个示例以脚本方式为开发者实现了一个引导页
* 示例请使用 Apploader 查看。

##开发指南

**Swipe.js 有以下几个参数**
<table>
<tr>
    <th>参数名</th><th>值</th><th>描述</th>
</tr>
<tr>
    <td>startSlide</td>
    <td>int</td>
    <td>起始图片切换的索引位置</td>
</tr>
<tr>
    <td>auto</td>
    <td>int</td>
    <td>设置自动切换时间，单位毫秒</td>
</tr>
<tr>
    <td>continuous</td>
    <td>boolean</td>
    <td>无限循环的图片切换效果</td>
</tr>
<tr>
    <td>disableScroll</td>
    <td>boolean</td>
    <td>阻止由于触摸而滚动屏幕</td>
</tr>
<tr>
    <td>stopPropagation</td>
    <td>boolean</td>
    <td>停止滑动事件</td>
</tr>
<tr>
    <td>callback</td>
    <td>function</td>
    <td>回调函数，切换时触发</td>
</tr>
<tr>
    <td>transitionEnd</td>
    <td>function</td>
    <td>回调函数，切换结束调用该函数。</td>
</tr>
</table>

* 推荐文档([http://www.jiawin.com/swipe-mobile-touch-slider](http://www.jiawin.com/swipe-mobile-touch-slider))