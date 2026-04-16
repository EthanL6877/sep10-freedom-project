# Tool Learning Log
3/17
### a-ha / challenges:
* Found out how to apply css with Jquery from [Tutorialspoint](https://www.tutorialspoint.com/jquery/index.htm)
```bash
   $(document).ready(function(){
 $("body").css("background-color", "yellow");
});
  ```
* I also found that Jquery and Java script use similar pieces of code but Jquery is a more simplistic and limited version where its limited to the same limits as **HMTL** & **CSS**.
### websites:
* [Tutorialspoint](https://www.tutorialspoint.com/jquery/index.htm)
  * I used the css part of the tutorial to help me apply css while only using **Jquery** code
* [FreeCodeCamp](https://www.freecodecamp.org/news/search/?query=jquery)
  * Allowed me to get a deeper understanding of how **Jquery** works   
### Facts:
* must always use ``` $(document).ready()``` for the start of every seperate line of code for Jquery
* must have a function and a variable to which the line of code can be affected by

### questions:
* How do I apply effects to my Jquery code, as in the duration and what effect takes higher priority?
* How can I make things toggle only on click?

### Next steps:
* Find out how to apply effects on Jquery code and to figure out how to toggle code with a click or motion.
_______________________________________________________________________________________________________________________________________
4/15-17
Day By day plan for learning tool final stretch:
days-->Wednesday, Thursday, Friday
*  day 1, Begin learning how to have a function have multiple variables and figure out how to make Jquery responsive through videos or websites
   * spend most of the time learning 
*  day 2, start using more complex code of Jquery that being how to include mainly CSS and animation while writing down any new ideas that could help with the freedom project site
   * Mainly learning but also note taking  
*  day 3, start actually writing down ideas and plans for FP site while breaking down what code will be used
   *  focus more on note taking than actual coding 

### a-ha / challenges:
* When looking through the Jquery code page I had a issue where the fade in for the shown code block below being delayed for a unknown amoount of time. I gave a look at the Jquery webpage to make sure if there was any way around this with minimal change and I found that for a single action there could be more than one function variable applied, with the delay I can change when the fadein does appear.
```bash
$(document).ready(function(){
  $("p").click(function(){ // when the p is clicked...

    // do this stuff
    $(this).toggle();
    $(this).delay( 200 ).fadeIn( 400 ); <--
  });
```
* 
### websites:
* 
### Facts:
* The order of functions for a single code block is from top to bottom
``` bash
$(document).ready(function(){
  $("p").click(function(){ // when the p is clicked...

    // do this stuff
    $(this).toggle();
    $(this).delay( 200 ).fadeIn( 400 );
  });
```
* Divs make a difference in how the animate functions works
* The ```.even``` function makes every even line of text or object colored
 * The first selected item is colored because it is considered "0"
### questions:

### Next steps:






3/23/2026

<!-- 
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
