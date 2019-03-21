# mycss
my notes when learning Css

## 布局
前端项目开发过程中非常重要的一环就是页面框架的搭建(即布局)，也是最基础的一环。在页面布局中，又有居中布局、多列布局以及全屏布局。
- 居中布局
    - 水平居中
        - inline-block + text-align
        - table + margin
        - absolute + transform
        - flex + margin
        - flex + justify-content
    - 垂直居中
        - table-cell + vertical-align
        - absolute + transform
        - flex + align-items
    - 水平垂直居中
        - absolute + transform
        - inline-block + text-align + table-cell + vertical-align
        - flex + justify-content + align-items
- 多列布局
    - 定宽+自适应
        - float + overflow
        - float + margin
        - float + margin(改良版)
        - table
        - flex
    - 两列定宽+一列自适应
    - 不定宽+自适应
        - float + overflow
        - table
        - flex
    - 两列不定宽+一列自适应
    - 等分布局
        - float
        - table
        - flex
    - 定宽+自适应+两块高度一样高
        - float
        - table
        - flex
        - display
- 全屏布局
    - position
    - flex
    - grid