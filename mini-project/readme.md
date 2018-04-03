# Project: Build a Flexbox Mixin with scss

I'm excited about this guide because in this guide I'm going to walk through some of the real power that you can get out of sass mix ins and how you can combine really a lot of the things that we've been learning throughout this course into one guide. And so what we're going to do is we're going to build a flexbox mix then.

Now if you've never heard of flexbox before that is perfectly fine. It will also be a nice introduction for you on how flexbox works. It's a very powerful way of writing your CSS code for doing things such as aligning items. If you've ever struggled with getting a title or something to line up in a central alinement or anything like that some things that seem like they'd be easy but can be surprisingly challenging. Fluxbox is a great option for modern front-end development. However, this is this guy is not about flex Xbox it's actually about something that I don't like about flexbox and so I decided to build a mix and in order to fix it.

So this is a prototype and a component I was building for dev camp and what is here is a set of cards and these cards have a title a subtitle they have an image and then they have some action item links. Now they look a lot better on dev camp. This was just a prototype before the designer got it and it has more to learn how flexbox could be used to do things like align these buttons here and to put an image here. If you try doing this just purely in CSS this would be a very challenging task so I utilize flexbox in order to do that. Now let's look at the CSS as we have here a display of flex for the entire container and I'm going to give you access to the HTML and the CSS so that you can see all of it first how it started. And then also how we're going to factor it. So we have this container and every time that you want something to utilize flexbox you have to say display flex so you can see that we have it here. Then we have this item class. We also have it here then we have this content item. We have it here, metadata. We have it here, button group. You kind of get the point. It is everywhere.

So each one of these elements and some of them are nested some of some of them are outside but all of them are in this container class. They have some form of a flexbox component whether it's one or whether it's four or five. And we need the ability to simply remove all that duplication and simply call a single mixin. You know everything that you need to know in order to do this I'm going to let you know the different components that we're going to be utilizing. So we're going to use the flex item, we're going to be using the display flex element here, we will use justify content we're going to use flex direction, and we have aligned items, that is it.

So each one of those items we are going to take and we're going to build into a mix and but as you may have noticed each component is a little bit different. They each need a different set of these values. So everything that you've learned so far whether it is just a standard mix in arguments default values conditionals all of those things are what you need in order to build this project. So you have access to the starter code here. But the well and the Scss while and I want you to go and take all of the Flexbox content out so each one of those items and put it into a mix and so that you only call a single mix and every spot that has flex box go through that do it. And then you can watch how I personally did it in the solution.

### The flexbox elements needed for the project are:
- display: flex
- justify-content
- flex
- flex-direction
- align-items


https://rails.devcamp.com/styling-scss/scss-mixins/1200
