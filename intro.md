One of the most powerful parts of using SCSS in development is the ability to make your code more efficient. If you're coming from a programming language such as Ruby or Python then the concept of having variables is a pretty common thing that you would implement into a program.

A variable is simply a container that can store a value and then can be called from anywhere else in the application. So you don't have to put identical code all through the entire app. So let's take a look at this basic example.

So you should already have your CSS lined up and have the SCSS property set so that it compiles and it can actually process the SCSS as opposed to simply treating it like regular CSS. What we are going to be talking about here are variables.

What we want to talk about is how we can leverage variables. If we look we can see that we have some duplication here. We have the background color and whenever you see six F's in a row that's going to be the color white. We also have this dark red color. All of this is fine but imagine that you have a CSS file that is a few thousand lines long. An example of that is if you pulled in some kind of template or you're building a template and the client informs you that he would like to change all the instances of dark red to dark green. This means that you would have to search and make sure you change every instance. Part of the logic behind using SCSS is the fact that you can implement the same type of mindset that Rails has with "Do No Repeat Yourself".

That's where variables come in. We would want to set our variables at the very top. Here we can see how we set variables in SCSS.

Now all we have to do is use that variable to change your styles across the CSS file. Imagine our client from earlier, now if he came to us with a change to make to our color scheme. We only have to change the value of that variable and it will reflect everywhere we used that variable.

We will go ahead and change the places that we had duplicate calls for ```#ffffff``` with out new variable.

Here is a demo where I use variables to manage the background color and font color for a page.

https://rails.devcamp.com/styling-scss/scss-basics/d6fab87d-7df1-4c23-af96-9d1fcdb5996d