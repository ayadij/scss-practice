This is a very powerful way of being able to dynamically change how mixins behave.

So great example is let's say we have this featured mix in here we want just about all of these things to be the same. The only thing that we want to be different is we want this color but we don't want to pass in the color.

I added a new argumnet called $bg-color: 'dark'

this is syntax for setting a default value for an argument in scss

```scss
@mixin featured($bg-color: 'dark') {
  @if $bg-color == 'light' {
    color: Tomato;  
  } @else if $bg-color == 'dark' {
    color: blue;  
  } @else {
    color: red; 
  }

```

I combined both of the conditionals into one. red is the other default 


https://rails.devcamp.com/styling-scss/scss-mixins/working-scss-conditionals
