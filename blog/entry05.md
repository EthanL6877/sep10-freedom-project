# Entry 5

### Content
In my tinkering, I used [**jQuery**](https://api.jquery.com/) to include interactive behavior. To explain what **jQuery** is, **jQuery** is a **JavaScript** library designed to make it easier to select elements, handle events, and create effects without writing as much complex code as compared to the much more bulky version of JavaScript. By using **jQuery**, I was able to apply changes to text, buttons, and other elements. One feature I used was event handling, which lets you run code when a user clicks or interacts with text or images, making the page feel more user responsive. I also used animation functions like **fadeOut, toggle, delay, and animate, mousedown, alert**, which allowed elements to smoothly disappear or move, with other functions like **Toggle and Delay** allowing me to change how the elements will function, while alert gave a notification depending on a requirement; if no requirement was given, it was set at the start of the page. Another important part of how **jQuery** works is that it uses simple selectors, similar to CSS, to target specific elements on a page. This made it much easier for me to control exactly what I wanted to change without affecting the rest of the webpage, especially with the fact that **jQuery** still works with normal CSS and HTML, letting me expand my range of abilities or simplifying the code so it isn't so messy/hard to look at.
``` bash

window.onload = function() {

    alert( "welcome" );

};

$(document).ready(function(){
  $("p").click(function(){ // when the p is clicked...

    // do this stuff
    $(this).toggle();
    $(this).delay( 200 ).fadeIn( 400 );
    $( "p" ).even().css( "background-color", "red" );
  });
});
$(document).ready(function(){
$(".yo").animate({height: '200px'}, 1000, function() {
    $(this).animate({width: '200px'}, 1000);
     $(this).animate({width: '1350px'}, 4000);

});
});
$(document).ready(function() {
   $("p.parent").mousedown(function(){
  alert("Mouse down over!");
});
});
```
Another thing I found was **Bootstrap components**. I used Bootstrap components to quickly design my site. Bootstrap is a compilation of premade components, making it easier to quickly build parts of a website without starting from scratch. By using Bootstrap, I was able to make my page **responsive**, meaning it could be adapted to different screen sizes. One component I used was the navbar, which helped me create a clean and organized navigation menu at the top of my page. I used **rows and columns** to arrange content in a neat layout that adjusts depending on the screen size. Another feature I used was the **carousel**, which allowed me to display images or content in a sliding format that users can interact with. Lastly, I used Bootstrap buttons to easily traverse through my website's elements that made my page more accessible. 
```bash
    <nav class="navbar navbar-inverse navbar-static-top" data-spy="affix" id="nav">
    
        <div class="container-fluid">
            <div class="navbar-header">
                <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#myNavbar">
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                </button>
            </div>
            <div class="collapse navbar-collapse" id="myNavbar">
                <ul class="nav navbar-nav">
                    <li><a href="#splash">Home</a></li>
                    <li><a href="#info">Info</a></li>
                    <li><a href="#gallery">Gallery</a></li>
                    <li><a href="#testimonials">Testimonials</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <div class="container" id="begin-content">
        <div class="jumbotron dark-brown row">
            <div class="col-sm-10">
                <h1>Fun for everyone</h1>
                <p>Come make a new memory with us. There's nothing else like it. </p>
                <p>Fun for both adults and kids. All are welcome!</p>
                <p>Afraid of heights? You won't be after you slow-dance with the sky.</p>
            </div>
            <div class="col-sm-2">
                <img src="../img/hot-air-balloon-clipart.png" class="img-responsive img-small center-block">
            </div>
        </div>
    </div>

```
### Googling
I really took my time searching what affects jQuery code and fell upon this [video](https://www.youtube.com/watch?v=2n5EBLBHx-A) on YouTube to better understand my tool, which was a real pain for being around an hour, which I took the liberty to skim through the more important parts, that being the HTML and the animate, since I'm using that for my Freedom Project. Another Site that I used was [tutorials point](https://www.tutorialspoint.com/jquery/index.htm) for both [Bootstrap](https://getbootstrap.com/docs/5.0/customize/components/) and Jquery understanding. For every part researched, I took the time to break down and practice, especially on the **Shabr** project.
### socializing
During the time I spent on the **Shabr** project I was with a partner and since we planned to separate what parts we were gonna each do I had to have learn what was needed, I did struggle on columns and rows which he then taught me how they worked with columns and rows following a grid system of 12 grid system.
### Problem Solving:
* Learnt how Jquery is affected by functions while implementing my very own ideas to shorten the amount of code required
* Bootstrap components allow for easier structuring of a website

[Previous](entry02.md) | [Next](entry04.md)

[Home](../README.md)

[Previous](entry03.md) | [Next](entry05.md)

[Home](../README.md)

Text

[Previous](entry04.md) | [Next](entry06.md)

[Home](../README.md)
