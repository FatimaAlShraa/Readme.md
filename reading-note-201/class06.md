## OBJECT

**WHAT IS AN OBJECT?**

is a  set of variables and functions to create a model of a something you would recognize from the real world
so how we can write object in literal notation :

var hotel = {

propareties and method 

};

and in dot notation:
 
let hotelName = object.properties/method

## The Document Object Model 

it's talk about howw browsers should create a model of an HTML page and how JavaScript can access and update the 
contents of a web page while it is in the browser window

### Dom tree 

Each branch of the tree ends in a node, and each node contains objects

![dom tree](https://www.tutorialstonight.com/assets/js/html-dom-tree-example.png)


+ getElementByld( 1 id 1) Selects an individual element in id

+ querySel ector( 1css selector')  select one or more elements 

+ getEl ementsByClassName( 1class 1 ) Selects one or more elements given the value of their cl ass attribute.

+ getEl ementsByTagName( 1tagName 1) Selects all elements on the page with the specified tag name.

+ querySelectorAll ( 1css select or•) Uses CSS selector syntax to select one or more elements and returns all 
of those that match


we can select element nodes by their id or class by tag name, or using CSS selector

* element node is a temporary harvestable structure can contain multiple text nodes
 
< script>
var node = document.createTextNode("This is new.");
< /script >

so from an element node, you can access and update its content using properties such as textContent 

![elementnode](https://i0.wp.com/www.javagists.com/wp-content/uploads/2017/09/java-tree-data-structure.png?resize=648%2C326&ssl=1)
