# mixin

SCSS has become so popular through the years, because it lets you wrap up functionality that you use quite a bit and call it from anywhere in the application.
So now we can make changes in our mixin and they are reflected where ever we have used them. Let's see how we can do the same thing down below for our Sidebar. So even though our Sidebar has a few items that are different and unique we can still just call these mixins and the system will do the remainder of the work for us.
personally like to think about mixins like a method where they can be called from anywhere in the application. I also liken them to very powerful variables, kind of like the way where we made a change to just one value of a variable at the very beginning and it populated to the rest of the application. Same thing with mixins. Now this is just one part of mix ins and this is very helpful to create reusable code components that can be called from anywhere else in any other SCSS file and you can just reuse those without having to copy and paste a full set of style definitions.

https://rails.devcamp.com/styling-scss/scss-mixins/creating-your-first-mixin