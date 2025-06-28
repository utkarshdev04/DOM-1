Dom stands document object model 
 dom abstracts the structure of a document into a tree of object and throught this script can manipulate the content and structure . 
 
Static website : websites which are once created and then no changes can be made to them . 
static website to-do listcode given . 

Dynamic websites : websites which html can be changed 
functions through which we can read DOM funcs

browser understands only html , css , js language 
we can use js in html by using <script>  js code block </script>
if we use console.log(document) the whole page block gets selected

we have learned about 2 important functions through which we can fetch contents of js 

1. querySelector : querySelector is a function through which single part of document block can
be selected and we can make changes to it.
 ex : document.querySelector("input");
the input box is selected .

 2. querySelectorAll : it is a function in which multiple parts of block having same tag can be selected at one and we can make chanes to them this returns array of parts which contain same tag.
    ex : document.querySelectorAll("h4")
    so this will select all the parts having h4 tag and return them in array form .

    we can apply css changes to a HTML page by using ids with html tags
    so here if we have to select among different ids we can do it as
    1. document.querySelector("#id1")
    2. document.getElementById("id1")

note :-> to create changes in a id we can do it by 
#todo 1 {
back-ground color : red ; 
}

we can create class of html tags by giving same  class to all of them ex : todo and apply css effect by 
.todo{ 
color : red ; 
}
here in console for accessing class 
document.querySelectorAll(".todo")
 and byanother fetching function as :
 
 document.getElementsByClassName("todo")
HTMLCollection(3) [h4.todo, h4.todo, h4.todo]

  important note : 
  whenever we are doing 
  querySelector("input").value through it the value can be print 
while through 
querySelectorAll("h4").innerHTML value gets print and querySelectorAll("h4").innerHTML = "asd"
value gets updated in page as well

setInterval : fn in js that calls a fun after given time interval infinetly 
setTimeout : fn in js that calls a fn only once after given time interval
