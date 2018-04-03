## @import Directive


- ex: https://github.com/jordanhudgens/daily-smarty/blob/master/app/assets/stylesheets/application.scss

This is a very common pattern you'll see where you have one master application Scss file and then it imports all kinds of other Scss files to be able to organize the code 


and it also accomplishes one other task that is very important. If you remember Cascading Style Sheets is what represent CSS that's the acronym. The whole **cascading** nature of stylesheets means that it's very easy to accidentally have one style override another one if you're using a framework such as the bootstrap framework like we're using right here it's incredibly important to be able to override certain styles that you don't want to keep.