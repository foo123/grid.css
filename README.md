# grid.css

Grid CSS Layout: a) with display *inline-block*, b) with display *flex* and c) with display *grid*

**example**

```css
.grid {
    --column-gap: 10px;
    --row-gap: 20px;
    --columns: 5;
}
@media (max-width: 1400px) {
.grid {
    --columns: 4;
}
}
@media (max-width: 900px) {
.grid {
    --columns: 3;
}
}
@media (max-width: 600px) {
.grid {
    --columns: 2;
}
}
@media (max-width: 400px) {
.grid {
    --columns: 1;
}
}
```

```html
<ul class="grid">
<li>1</li>
<li>2</li>
<li>3</li>
<li>4</li>
<li>5</li>
<li>6</li>
<li>7</li>
<li>8</li>
<li>9</li>
<li>10</li>
<li>11</li>
</ul>

<ul class="grid flex-layout">
<li>1</li>
<li>2</li>
<li>3</li>
<li>4</li>
<li>5</li>
<li>6</li>
<li>7</li>
<li>8</li>
<li>9</li>
<li>10</li>
<li>11</li>
</ul>

<ul class="grid grid-layout">
<li>1</li>
<li>2</li>
<li>3</li>
<li>4</li>
<li>5</li>
<li>6</li>
<li>7</li>
<li>8</li>
<li>9</li>
<li>10</li>
<li>11</li>
</ul>
```

**output**

![demo test](/screenshot.png)

**see also**

[responsive.css](https://github.com/foo123/responsive.css)
