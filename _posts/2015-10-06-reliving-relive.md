---
layout: post
title: Reliving Relive
---

Assignment 3 ended at the end of the recess week and I'm glad I learnt quite a bit from developing Relive. Here are 3 things that made an impression on me throughout these few weeks.

# Sass - "CSS with superpowers"
<br>
![sass](http://sass-lang.com/assets/img/illustrations/glasses-2087d741.svg)

I've been the frontend developer for both Assignment 1 & 3, and so far, learning Sass has been invaluable. From learning the very basics of Sass, I'm unlikely to use CSS on its own anymore.

If you don't know what Sass is, it's basically CSS on steroids. Sass adds functionalities to CSS to make it easier to add and organise styles. Sass solves many pain points about CSS.

CSS does not allow for variables. This causes CSS to be difficult to maintain as it grows. Imagine having a primary colour for your app which is used in various components such as buttons, headers, backgrounds, etc. Let's say you decide to change the primary colour. Although you could find all occurrences of the old hex value and replace them, having a `primaryColour` variable will make such updates trivial and also gives meaning to hex values.

CSS also doesn't allow nesting of styles. For example, you may have some components that belong to the same parent component. Sass allows you to organise your CSS in a way that expresses the hierarchy of such relationships. This also increases the maintainability of your CSS.

Sass also has some pretty nifty functions that will make your live much easier. `darken` & `lighten` are two examples. They allow you to input a colour (e.g `primaryColour`) and specify how much darker or lighter the output colour should be. This makes it very easy to add things like shadows to button states which depend on the colour of the original button. Changing the colour of buttons also ensures that the other states of the button have their styles updated. Super powerful.

# "Do One Thing and Do It Well."
<br>
![framework7](http://www.idangero.us/framework7/i/logo-new.png)

Although this pretty much sums up what our ideas should serve to do, to solve one problem and solve it well, I found that the technologies we use should live up to that philisophy as well.

For Relive, we used Framework7. It's components are nice, and the functionality it provides is good. Customisation of the styles of the components is also pretty straightforward. My only gripe is that it tries to do a lot, yet doesn't do any of it very well.

My original impression of Framework7 was yet another CSS framework that contains common components that we can then extend. Framework7 actually does way more than that. It's more like a JS framework.

Framework7 uses its custom Dom7 DOM library for DOM manipulation. It basically replaces jQuery. However, I found that some functionality in jQuery couldn't be replicated with Dom7. Their documentation, although provides examples, the function I needed lacked any examples. Google wasn't of much help either.

Framework7 also uses Template7 which is a templating engine like Handlebars. I intended to use it to separate the HTML and the JS for better organisation and maintainability. Sadly, their documentation was minimal and we couldn't figure out how to use it. Ultimately, we didn't have time to fuss about the separation of HTML & JS and had to leave HTML in our JS.

One thing I like about Framework7 is it's components. They look good on iOS and can be easily styled to fit our needs. It also has some transitions that work well and make the app look native.

As such, if Framework7 can be integrated with some other JS framework, I think it'll be perfect; Framework7 can handle the components while the JS framework can handle routing, api calls, etc.

# App names are important

"Our app is called relive.", "relief?", "No, r-e-l-i-v-e".
I've encountered that a couple of times when explaining it. Explaining the app quickly was certainly a challenge.

I think it's important to create applications with unique yet recognisable names. Names that are hard to spell or are unrelated to the app doesn't provide any advantage at all.

Also, we chose ".space" as our top level domain. Although it sounds alright ("relive space"), it would be much better to have a domain name that is simpler ("relive.com"). Too bad it was already taken.

By having a recognisable app/brand name, people will be more likely to remember it and marketing becomes much more manageable.

---
All in all, I enjoyed Assignment 3. I'm now looking forward to our final project, (we haven't finalised it's name yet)!