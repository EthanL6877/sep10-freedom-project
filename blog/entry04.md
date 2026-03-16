# Entry 4
### Content(JQuery)
In my **tinkering**, I used jQuery to add different interactive features to my webpage. jQuery is a **"JavaScript library"** that is meant to simplify the control over elements on a webpage and create effects without writing a lot of code. By using jQuery, I was able to make my page more dynamic by adding different features to each line of text.

the first feature I used was **toggle**. The **toggle** function lets you show or hide content when a user clicks a button or another element. In my tinkering, I used **toggle** so when I clicked a button, a section of text would appear, and when they clicked it again, the text would disappear.
2nd feature I used was **fadeIn**. The **fadeIn** effect makes elements slowly appear on the screen instead of just popping up instantly. I used **fadeIn** to make the text appear gradually when the text is clikced thats why I added it to the toggle command as without it the text when clicked on would remain gone until the page was reloaded. 

``` bash
$(document).ready(function(){
  $("p").click(function(){
    $(this).toggle();
    $(this).fadeIn();
  });
});

```

3rd feature I used was **Animate** function. **Animate** lets you change different properties of an element, like its size, position, or opacity, over time. In my tinkering, I used **Animate** to move an element across the screen when the page is first opened and return to its original size. Depending on the amount of time given to each element it allows for me to give the selected text the ability to do whatever I want with how its shaped.
``` bash
$(document).ready(function(){
$(".yo").animate({height: '200px'}, 1000, function() {
    $(this).animate({width: '200px'}, 1000);
     $(this).animate({width: '1350px'}, 4000);
});
});
```

The last thing I used was the **mousedown** event. The **mousedown** event happens when a user presses down on their mouse button and creates a notification for a page. I used this to trigger an action when the user clicked on a specific element. For example, when the user pressed the mouse button on an object, it would bring up a notification on the page with whatever I wanted it to say.

``` bash
$(document).ready(function() {
   $("p.parent").mousedown(function(){
  alert("Mouse down over!");
});
});

```
### Googling
For my googling skill I was struggling as sites for when I tried searching for information on **JQuery** was a limited to just the [original site](https://api.jquery.com/) and [w3schools](https://www.w3schools.com/jquERy/default.asp). However as I kept tinkering I kept wondering what if their was anything I was missing so I searched fo "JQuery help" and found a great site called [tutorialspoint](https://www.tutorialspoint.com/jquery/index.htm) it helped with alot of the issues that came along with tinkering.

### socializing
My socializing skill was well developed not in the way you might think as during my tinkering all of the coworkers I knew didn't use JQuery for its supposed complicated design. I instead took the time to talk with coworkers how they used their tool and observed how they used it so I can potentially apply it to my own work, while it wasn't all that helpful it still gave me some insight to others tools.

### Problem Solving:
I Struggled much with **JQuery** as it broke easily when soemthing was missing compared to the regular **HTML** that I was used to a main issue was that everytime I had to add a different event it required me to have ``` $(document).ready(function() {});}); ``` at the top of each piece of code for the line to run. Another issue I had was that I couldn't figure out how to apply a duration so there was a dely in animation or the fade in/out which google didn't provide much help in. Instead I took the time to search these sites [tutorialspoint](https://www.tutorialspoint.com/jquery/index.htm), [w3schools](https://www.w3schools.com/jquERy/default.asp), [original site](https://api.jquery.com/) in which I eventually found my answers to both of my issues although it took hours of trial and error.

[Previous](entry02.md) | [Next](entry04.md)

[Home](../README.md)

[Previous](entry03.md) | [Next](entry05.md)

[Home](../README.md)
