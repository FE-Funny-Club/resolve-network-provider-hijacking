# resolve-network-provider-hijacking
解决万恶的运营商劫持

## 通用隐藏样式
受到运营商的网络劫持后，可能会在页面中注入一些广告的 DOM，可以使用下面的 css 来隐藏掉

```css
/**
 * 隐藏中国移动的脚本劫持 dom
 */
body .tlbs,
body .ts-animatedd,
body #tlbstoolbar,
body tlbs-flux,
body iframe,
body #_ta_qaz_wrap {
    display: none!important;
}
```
