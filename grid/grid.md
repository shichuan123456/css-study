# Grid layout

## 容器属性

 1. display: grid | inline-grid 子元素的布局属性失效
 2. grid-template-rows: px | percent | repeat(auto-fill, 100px), repeat(3, 33.33%), repeat(2, 10px 200px 40px) | fr |
 minmax(100px, 1fr) | auto | [c1] 100px [c2] 100px [c3] auto [c4] | [r1] 100px [r2] 100px [r3] auto [r4]
 3. grid-template-columns: 同上
 4. grid-row-gap: 行间距
 5. grid-column-gap: 列间距
 6. grid-gap: <grid-row-gap> <grid-column-gap>
 7. grid-template-areas: 'a b c' 'd e f' 'g h i'
 8. grid-auto-flow: row dense | column dense
 9. justify-items: start | end | center | stretch
 10. align-items: start | end | center | stretch
 11. place-items: <justify-items> <align-items>
 12. justify-content: start | end | center | stretch | space-between | space-evenly
 13. align-content: start | end | center | stretch | space-between | space-evenly
 14. place-content: <justify-content> <align-content>
 15. grid-auto-columns:
 16. grid-auto-rows:

 17. grid-auto-columns:

## 项目属性

1. grid-column-start
2. grid-column-end
3. grid-row-start
4. grid-row-end
5. grid-row
6. grid-column
7. grid-area: <row-start> / <column-start> / <row-end> / <column-end>
8. justify-self:
9. align-self:
10. place-self: <justify-self> | <align-self>
