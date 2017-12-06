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
Desktop
```
@media screen and (min-width:768px){
  .element{
    background-attachment: scroll;
  }
}
```

## Mazonry

Container
```
.mazonry{
  column-count: 1;
  column-gap: 0;
}
```
Items
```
.item { /* Masonry bricks or child elements */
    background-color: $primary-color-light;
    display: inline-block;
    margin: 0 0 1em;
    width: 100%;
}
.item img{
  /*adding responsive to images*/
  width:100%;
}
```
Desktop
```
@media screen and (min-width:768px){
  .mazonry{
    /*Number of columns desired*/
    column-count: 3;
    column-gap: 0;
  }
}
```
