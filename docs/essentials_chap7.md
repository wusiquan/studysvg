#### svg使用脚本

首先，当然是获取结点 document.getElementById(idString)

* 获取属性值(字符串) `element.getAttribute(attributeName)`
* 改变(创建)属性值 `element.setAttribute(name, newValue)`
* 移除属性 `element.removeAttribute(name)`

用element.style来调整内联样式

* `element.style.getPropertyValue(propertyName)` 获取特定样式

* `element.style.setProperty(propertyName, newValue, priority)`来改变样式

  (priority通常为nul, 可以设为"important")

* `element.style.removeProperty(propertyName)`来删除样式

`element.style.cssText` 一次设置所有样式

`element.textContent` 获取或修改任何结点文本内容


[例子](https://wusiquan.github.io/studysvg/examples/essentials_chap7/1.html)

