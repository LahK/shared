# JavaScript 坑

- 绑定 click、mouse、drag 事件时，注意考虑清楚绑定对象的选择。子元素事件会触发父元素事件，记得做相应处理。
- 获取指定 id 元素样式值时，用 var eleStyle =  window.getComputedStyle(ele)。
- dragable 元素记得加上 draggable="true"。
