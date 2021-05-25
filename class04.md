# Links

## ( link syntax )

** < a href=" urlLink">IMDB< /a> **
* Links are created using the < a > element.

## ( Path )
1. Every page and every image on a website has a URL . The URL is made up of the domain name followed by the path to that page or image.

2.we use URLs when linking to other web pages and when including images in our own site. 


### ( target )
If we want a link to open in a new window, we can use the target attribute on the opening < a > tag. The value of this attribute should be _blank.

** example : ** 

** < a href="url" target="_blank" > **

### Notes : 

* The  < a > element uses the href attribute to indicate
the page you are linking to.

* If we want to linking to a page within own site, it is
best to use relative links rather than qualified URLs.

* we can create links to open email programs with an
email address in the "to" field.

* we can use the id attribute to target elements within
a page that can be linked to.

# ( LAYOUT )

* ### Block-level elements
start on a new line.
Examples include:
< h1 > , < p > , < ul > , < li >

* ### Inline elements
flow in between surrounding text.
Examples include:
< img >, < b > ,< i >


##  ( Controlling the Position of Elements )
> CSS has the following positioning schemes that allow us to control
the layout of a page

1. Normal flow  
Every block-level element appears on a new line, causing each item to appear lower down the page than the previous one.

2.  Relative Positioning 
This moves an element from the position it would be in normal flow, shifting it to the top, right, bottom, or left of where it would have been placed.

3.  Absolute positioning 
This positions the element in relation to its containing element.


## ( box offset )
** we use it to indicate where a box should be positioned. **

1.  Fixed Positioning 
This is a form of absolute
positioning that positions
the element in relation to the
browser window, as opposed
to the containing element. 


2.  Floating Elements 
Floating an element allows you to take that element out of normal flow and position it to the far left or right of a containing box.



# ( Functions )
> Functions let us group a series of statements together to perform a specific task.

### Function Syntax :
function myFunction(p1, p2) {

  return p1 * p2;   // The function returns the product of p1 and p2

}



## ( Declaring A Function )
when we creat a function we must give it a name and then write the statments needed to achive its task inside the curly braces. and this is known as a ( Declaring A Function ) .

*  FUNCTION DECLARATION 
> example :

function area(width, height) {

return width * height; 

};

var size= area(3, 4);

*  FUNCTION EXPRESSION 
> example :

var area =  function(width, height) {

 return width * height;

 } ;

 var size=  area(3, 4);


## ( VARIABLE SCOPE )
* The location where we declare a variable will affect where it can be used within our code. If we declare it within a function, it can only be used within that function. This is known as the variable's scope. 

* 1. LOCAL VARIABLES 

When a variable is created inside a function using the var keyword, it can only be used in that function.It is called a local variable or function-level variable. It is said to have local scope or function-level scope.It cannot be accessed outside of the function in which it was declared.


* 2. GLOBAL VARIABLES 
If we create a variable outside of a function,then it can be used anywhere within the script.It is called a global variable and has global scope.


# ( Code Fellows )
* when we useing Code Fellows we work on all of language-specific skills.The abilities they foster will serve us well in completing assignments,in own communication and learning,in interviews, and in readiness for a job at 
a company that utilizes this agile practice.

*  we will learn : 
1. Greater efficiency
2. Engaged collaboration
3. Learning from fellow students
4. Social skills
5. Job interview readiness
6. Work environment readiness



( References that i used )
[Duckett HTML book](https://wtf.tw/ref/duckett.pdf)

[Duckett JS book](https://ltuc-asac.slack.com/files/U019NRDFF97/F022SGL4CKV/duckett_html__1_.pdf)

[Code Fellows](https://www.codefellows.org/blog/6-reasons-for-pair-programming/)

 






