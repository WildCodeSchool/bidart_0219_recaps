# Recaps Week 3

## Crew:  
Sarah, Florian, Marlene, Jim, Sylène, Nathalie, Jonathan, Cloé , Stephane V.
  
  
 
## What is JS
Javascript (JS) is a scripting languages, primarily used on the Web. It is used to enhance HTML pages and is commonly found embedded in HTML code. JavaScript is an interpreted language. Thus, it doesn't need to be compiled. JavaScript renders web pages in an interactive and dynamic fashion. This allowing the pages to react to events, exhibit special effects, accept variable text, validate data, create cookies, detect a user’s browser, etc.  
  
***Origin:***  
It was invented by Brendan Eich, co-founder of the Mozilla project, the Mozilla Foundation, and the Mozilla Corporation.  
It was developed under the name ***Mocha***, the language was officially called ***LiveScript*** when it first shipped in beta releases of Netscape Navigator 2.0 in September 1995, but it was renamed ***JavaScript***  
  
***What is it use for***:  
JavaScript translates your static page into one that can interact with your visitors without them needing to wait for a new page to load every time they make a request.  
IN SUMMARY: JavaScript is a language to program the behavior of web pages.  

## Variables
Variables are used to store information to be referenced and manipulated in a computer program.
A variable name must start with a lower case character or $ or _.

*kind of variables*
	var: former way to declare a variable. 
	let: New way to declare a variable which can change.
	const: Declare a "immutable" (constant) variable.
	
*variable type (primitive)*
	pattern: (let or const)	(name of the variable in camelCase or snake_case) = (value);
	number : any number, integer or float, positive or negative.
		Ex: 10, -20, 34.57...
	string : chain of characters. You can use simple(')  or double (") quote for the declaration.
		Ex: "I love bananas...", "10", 'Toto is my boss' 
	boolean: Can be "true" or "false". Any value different from false, 0 or undefined are true.
		Ex true: true, 15, "toto"
		Ex false: false, 0

**Arrays**
	An array is a way to store multiple data in a unique variable.
	Any type of variable can be inserted in an array.
	An array can be declared using "let" or "const". In this case (const), the content of the array can change but the type have to stay the same.
	How to declare an array:
		 ```javascript
		 let myArray = ["toto", 3, false,[ 1, 2, 3]];
		 ```
	How to access to an item in an array:
		```javascript
		let myArray = [ 1, 2, 3, 4];
		console.log(myArray[3]) ;``` --> it returns "4". As a reminder, the index starts at 0 !!
		How to change an item in an array:
		```javascript
		const myArray = [ 1, 2, 3, 4];
		myArray[3] = 10;
		console.log(myArray[3])``` --> The item at index 3 has been set to 10.
	How to add a new item into an array:
		.push() --> Add an item at the end of the array
		.unshift() -->  Add an item at the beginning of the array
	How to remove an item from an array
		.pop() --> Remove the last item from the array
		.shift() --> Remove the first item from the array



______________________________________________________


## A completer  par un autre crew (have fun!!)

conditions - if then else

loops
	- for
	- while / do While
	- switch/case

fonctions

objets (JSON)
{
	"nom" : "toto",
	"age" : 15,	
}

ES6
