
<!-- README.md is generated from README.Rmd. Please edit that file -->

# LearningRessources

# SaSS

\#\#SaSS Nesting

![](pictures/sass_nesting.jpg)

<br>

![](pictures/sass_nesting2.jpg)

## SaSS mixins

`@mixin` and `@include`

![](pictures/sass_mixins.jpg)

## @if , @if else and @else

``` css

<style type='text/scss'>

@mixin border-stroke($val){

  @if $val == light {

    border: 1px solid black;

  } 
  
  @else if $val == medium {

    border: 3px solid black;

  } 
  
  @else if $val == heavy {

    border: 6px solid black;

  } 
  
  @else {

    border: none;

  }



}

  #box {
    width: 150px;
    height: 150px;
    background-color: red;
    @include border-stroke(heavy);
  }
</style>

<div id="box"></div>
```

## SaSS @for

![](pictures/sass_@for.jpg)

## SaSS @each

![](pictures/sass_@each.jpg)
