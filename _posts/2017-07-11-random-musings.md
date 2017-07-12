---
layout: post
title:  "Random Musings"
date:   2017-07-11
excerpt: "What if when you looked a variable or a function you knew roughly what was contained inside of them"
image: "images/post-images/codes.jpg"
tag:
- code
- future
---

I ponder a lot about JavaScript usually it goes something like "Wait… What? Why is that not… I hate this language. Who TF thought using this was a good idea?!" And every time that happens I inevitably end up asking myself "Why don't we do better than this?" Which is something that's always piqued my interest. I'm fairly good at taking small pieces of complex material, distilling them to their purest form, and building something better in the place of the old way of doing things. 

What fascinates and infuriates me about developers is that for decades we have built stunningly beautiful and world altering ways to interface with computers. Yet we haven't even scratched the surface on what could be done if we turned that same eye towards our own trade and tools. It's 2017 how is it possible that text editors have barely changed? Sure there are way more plugins and fancy colors, but outside of that what's drastically different?

As I've looked at this problem a couple of things are apparent to me. 1) Syntax has gone as far as it's going to go in terms of becoming more human at least for the foreseeable future. 2) The onus to improve shouldn't have been on syntax anyway. The editor needs to be the thing that demystifies code for the user. 

Let take a look at some code:

```javascript
// Assign a String to a variable
var someVar = "This is my amazing String!!"

// Call Variable
someVar

someVar
```

Did you notice anything? No? Well the first thing that jumps out at me is there's a string assigned to this variable. That string has a lovely green color denoting to everyone that "Hey! I'm a string!". But when you call the variable you'll notice it's black. This has to be one of the simplest, yet glaring quality of life improvements I've ever seen in my life. What if when you looked a variable or a function you knew roughly what was contained inside of them because the color corresponded to the assignment? HOLY SHIT WHAT A NOVEL IDEA!

Instead of having a series of random, though oddly soothing, colors just strewn about. Assign colors based on the type of object conatained within. That way when you're glancing at a bloated document instead of going "wait wtf does this function do again?" You know at the very least "Ah that returns a number"

I also feel very strongly about having some kind of feedback loop. [Bret Victor](http://worrydream.com/) is a genius and I feel like he's absolutely right in most of his musings. Programming is the only art where you don't get to see your work in realtime as you're creating it. I'm not sure what something like this should look like but I know Swift playgrounds and interactive repls are a step in the right direction. At no time should you not be able to tug at different parts of your code to see what's contained inside of it. 

Something that would work well in conjunction with the aforementioned setup is the ability to focus on a chain of code. So say I have a function calling another series of functions. Not the entirety of my program, but a large chunk of it. At any point in time one should be able to to isolate the function summoning these other functions in a focus mode that fades out the rest of the program so that I can clearly observe what's being called and in what order.

I would go a lot further than this and implement not a language in itself but a language interface. Something that would add graphical enhancements that could be used on any language creating a unified look and feel for how code behaves. I've actually got some mockups that I may share at somepoint and explain in further detail. But for now the next frontier of coding is in our tools waiting to be unlocked to improve us as developers
