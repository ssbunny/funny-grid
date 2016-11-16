# funny-grid
简单实用的CSS网格系统。


使用样式 `grid` 表示网格，使用样式 `row` 表示一行，使用样式 `column` 表示一列。使用 12 列平分一行，因为这样w可以最便捷地实现平分、三等分、四等分。

```html
<div class="grid">
    <div class="row">
        <div class="column">1</div>
        <div class="column">2</div>
        <div class="column">3</div>
        <div class="column">4</div>
    </div>
</div>
```

使用 `w*` 表示所占的列宽数，如实现平分列：

```html
<div class="grid">
    <div class="row">
        <div class="column w6">左</div>
        <div class="column w6">右</div>
    </div>
</div>
```
