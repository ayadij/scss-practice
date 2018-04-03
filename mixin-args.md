Setting arguments inside of mixins:

There are times where you may simply want to have access to a set of styles and to be able to call this mix and from anywhere and that's perfectly fine. However there are many times where you want to change that behavior just a little bit. You may want to have some type of dynamic behavior and that's what we can leverage arguments that we can pass right into our mixins. 


```scss
      .sidebar {
        font-family: Verdana;
        text-align: right;
        float: right;
        width: 25%;
        @include featured(MintCream);
      }
      ```



https://rails.devcamp.com/styling-scss/scss-mixins/introduction-mixin-arguments-scss