# 容器的属性
  ## display: flex;
  ## flex-direction: row | row-reverse | column | column-reverse;
  ## flex-wrap: nowrap | warp | wrap-reverse;
  ## justify-content: flex-start | flex-end | center | space-between | space-around; 主轴
  ## flex-flow: <flex-direction> | <flex-wrap>;
  ## align-items: flex-start | flex-end | center | baseline | stretch; 交叉轴
  ## align-content: flex-start | flex-end | center | space-between | apace-around | stretch; 多根轴线的对齐方式

# 项目的属性
  ## order: <integer>; 数值越小越靠前
  ## flex-grow: 放大倍数，默认为0，如果存在剩余空间，也不放大。
  ## flex-shrink: 缩小的倍数，默认为1，等比例缩小，为0则不缩小。
  ## flex-basis: 在分配多余空间前，项目占据主轴的空间。浏览器根据这个属性来判断主轴是否还有多余的空间。
  ## flex: none | <'flex-grow'> <'flex-shrink'> <'flex-basis'>
  ## align-self: auto | flex-start | flex-end | center | baseline | stretch                                           
