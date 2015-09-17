#Naming Conventions To Create Clean Code

##Rules
 * [ Use intention-revealing names ]() 
 * [ Avoid disinformation ]() 
 * [ Make meaningful distinctions ]() 
 * [ Use pronounceable names ]() 
 * [ Use searchable names ]() 
 * [ Avoid encodings ]() 
 * [ Avoid mental mapping ]() 
 * [ Don’t be cute ]() 
 * [ Pick one word per concept ]() 
 * [ Don’t pun ]() 
 * [ Use solution domain names ]() 
 * [ Use Problem Domain Names  ]() 
 * [ Add Meaningful Context ]() 
 * [ Don't Add Gratuitous Context ]() 
 
##Examples

###Use Intention-Revealing Names 
**Intention-Revealing** names are variable, function, and class names that tell other developers (And sometimes the creator) clearly what they do and their intentions.

"You know are working on clean code when each routine you read turns out to be pretty much what you expected" - <sub>1</sub>

####Fictional Example
````javascript
//Loads page with list of names and returns the list element
var loadUrl = function(url){
    var $container = $('.container');
    $container.load(url);

    var listElement =  $container.find('ul');
    return listElement;
};
````

In the code above, the function does more than just load a url.

It:
* Loads a url
* Fills the container element with the content loaded from the url
* Gets the list of names and returns them.

>NOTE: Functions should be as short as possible (see function section)

###Avoid Disinformation

###Make Meaningful distinctions

###Use pronounceable names 

###Use Searchable Names 

###Avoid Encodings

###Avoid Mental Mapping

###Don't Be Cute

###Pick one word per concept

###Don't Pun 

###Use Solution Domain Names 

###Add Meaningful Context 

###Don't Add Gratuitous Context 




