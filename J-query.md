

187. incoperate to website:

## This is a CDN script from Google.
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>


## if we place the scripts in the head section, we need to add this line of code, to make sure that out code will execute just after the J-query code
$(document).ready(function(){ PLACE HERE ALL THE CODE });

## Minify the code- mean to get rid of all the unnecessary spaces- in order to spead up the code.


189. $
$("button"); = document.querySelector("button") = querySelectorAll("button);

190. Classes Manipulation

# Get The style
console.log($("button").css("color"));

# Change the Style
$("button").css("color", "green");



# add class to select element
$("button").addClass("class");
$("button").removeClass("class");

or multiple classes
$("button").addClass("class class2");

# check if element has class
$("button").hasClass("class");
//return true or false



191. Text manipulation;

## change text only
$("button").text("This is text"); = document.querySelector("button").textContent = "This is Text";

## change HTML
$("button").HTML("<em>This is text</em>"); = document.querySelector("button").innerHTML = "<em>This is text</em>";

192. Attributes manipulation;

# Get attribute
console.log($("img").attr("src"));

# set attribute
$("img").attr("src", "sky.png");

# get input value:
$("input").val();



193. Event Listeners.

# when button clicked, the h1 color will change to red.
$("button").click(function(){
    $("h1").css("color", "red")
})

# We can also set it on keypress.
$(document).keydown(function(event){
    console.log(event);
})


# Here i'm changing h1's text to the text inside the input:

$("input").keydown(function () {
    $("h1").text($("input").val());
});



# in general we can use the JQ "on" instead of the JS addEventListenter
$("h1").on("mouseover", function(){
    $("h1").css("color", "green");
})

194. elements Manupulation

# add element after the h1 close
$("h1").before("<button>Button</button>");
$("h1").after("<button>Button</button>");

# add element inside the h2 before and after the h1's text
$("h1").prepend("<button>Button</button>");
$("h1").append("<button>Button</button>");

# remove element
$("h1").remove();

195. Animations:


# hide (display:none) or show element:

$("h1").hide(); //  = display: none;
$("h1").show();
$("h1").toggle();

## hide a show animation.
$("h1").fadeToggle(); //fade out, and fade in.

## hide and show, slide animations.
$("h1").slideUp(); //disapear
$("h1").slideDown(); //show up


## general animation method
$("h1").animate({opacity: 0.5}) 
// the animate method get just propertise with numeric value, 
//for example it impossible to animate color change.

## add few animations to element.
// few animations:
$("h1").slideUp().slideDown().animate("opacity: 0.8");

