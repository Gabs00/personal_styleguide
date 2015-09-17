#Naming Conventions To Create Clean Code

##Rules <sub>1</sub>
 * [ Use intention-revealing names ](#intention-revealing-names)
 * [ Avoid disinformation ](#avoid-disinformation)  
 * [ Make meaningful distinctions ](#pronounceable-names) 
 * [ Use pronounceable names ](#meaningful-distinctions)
 * [ Use searchable names ](#searchable-names) 
 * [ Avoid encodings ](#avoid-encodings) 
 * [ Avoid mental mapping ](#avoid-mental-mapping) 
 * [ Don’t be cute ](#dont-be-cute) 
 * [ Pick one word per concept ](#one-concept-per-word) 
 * [ Don’t pun ](#dont-pun) 
 * [ Use solution domain names ](#solution-domain-names) 
 * [ Use Problem Domain Names  ](#problem-domain-name) 
 * [ Add Meaningful Context ](#meaningful-context) 
 * [ Don't Add Gratuitous Context ](#gratuitous-context) 
 
##Examples

###Use Intention-Revealing Names <a name="intention-revealing-names"></a>
**Intention-Revealing** names are variable, function, and class names that tell other developers (And sometimes the creator) clearly what they do and their intentions.

"You know are working on clean code when each routine you read turns out to be pretty much what you expected"<sub>2</sub>

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

###Avoid Disinformation <a name="avoid-disinformation"></a>

###Make Meaningful distinctions <a name="meaningful-distinctions"></a>

###Use pronounceable names <a name="pronounceable-names"></a>

###Use Searchable Names <a name="searchable-names"></a>

###Avoid Encodings <a name="avoid-encodings"></a>

###Avoid Mental Mapping <a name="avoid-mental-mapping></a>

###Don't Be Cute <a name="dont-be-cute"></a>

###Pick one word per concept <a name="one-concept-per-word"></a>

###Don't Pun <a name="dont-pun"></a>

###Use Solution Domain Names <a name="solution-domain-names"></a>

###Add Meaningful Context <a name="meaningful-context"></a>

###Don't Add Gratuitous Context <a name="gratuitous-context"></a>



#Credits 
1. Clean Code, PG VII, Ch. 2 TOC, by Robert C. Martin
2. Clean Code, PG 11, Ward Cunningham quote on clean code.
