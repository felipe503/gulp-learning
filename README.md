# gulp-learning
`gulp watch, autocompilate scss into css`

## parallax effect
First important rule
```
html, body{
  height: 100%;
}
```
Rules in element
```
.element{
  position: relative;
  background-position: center;
  background-size: cover;
  background-repeat: no-repeat;
  /*
    fixed : parallax
    scroll: normal
  */
  background-attachment: fixed;
}
```
