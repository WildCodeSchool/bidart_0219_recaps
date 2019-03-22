


**Crew**:
Sarah
Sylène
Marlène


**Key words of the week**
#Object-oriented programming
#Paradigm
#Encapsulation
#Modeling
#ES6
#Dojo
#NodeJS
#Express

---------------------------------------------------------------------------------------------------
**OOP**: Object-oriented programming / **

**What is it and what's the concept**:

 - The basis for OOP started in the early 1960s, 
 - 
  - Object-oriented (OO) programming is a programming **paradigm** that
   includes or relies on the concept of **objects,** **encapsulated data
   structures** that have properties and functions and which interact
   with other objects.
   
   -In the class-based **object-oriented** programming paradigm, **object
   refers to a particular instance of a class** where the object can be
   a combination of variables, functions, and data structures.
   
  - A good understanding of OOPs' concept **can help in *decision
   making*** when designing an application.  Objects in a program
   frequently represent **real-world** object, That' why we are writing
   coding ,to solve our real world problem right.


**How to use it:**:

 **Object:** It’s the instance of a class/ it’s the working entity of a class. ####
  **Class:** It is a template or blue print about the capability of what an object can do. #### 
  **Method:** The behaviours of a class. It tells what a method can do. #### 
  **Instance:**  Object and Instance both are same with small difference.  Instance is an object that has been created and exists in memory.

**Short Conclusion for OOP:**
1. EverythingIsAnObject 
2. Objects communicate by sending and receiving messages (in terms of objects). 
3. Objects have their own memory (in terms of objects). 
4. Every object is an instance of a class (which must be an object).*


------------------------------------------------------------------------------------------------------------------------------------------------

**Crew**:
Baptiste and Vanessa.

**Functional Programming in JavaScript: filter, map and reduce methods** :thumbsup:
There are 3 main methods for functional programming in JavaScript: filter, map and reduce. All these methods are applicable to arrays. Making use of these methods we could extract information from an array and the elements it contains to create new arrays without modifying the original array. 

**Description and Syntax**

- **Filter method**: filter() calls a provided callback function once for each element in an array, and constructs a new array of all the values for which callback returns a value that coerces to true. callback is invoked only for indexes of the array which have assigned values; it is not invoked for indexes which have been deleted or which have never been assigned values. Array elements which do not pass the callback test are simply skipped, and are not included in the new array.
```
let newArray = arr.filter(callback(elements, *index*, *array*){
  return each elements which condition is true;
})
```

- **Map method**: map calls a provided callback function once for each element in an array, in order, and constructs a new array from the results. callback is invoked only for indexes of the array which have assigned values, including undefined. Callback is invoked with three arguments: the value of the element, the index of the element, and the Array object being traversed.

```
let newArray = arr.map(function callback(currentValue, *index*, *array*) {
    return elements for new_array;
})
```

- **Reduce method**: reduce() executes the callback function once for each element present in the array, excluding undefined in the array, receiving four arguments:

- accumulator
- currentValue
- currentIndex
- array

```
let myVar = arr.reduce(callback(accumulator, currentValue, *currentIndex*, *array*){
  return accumulator;
})
```

*callback*
Function to execute on each element in the array, taking four arguments:

*accumulator*
The accumulator accumulates the callback's return values; it is the accumulated value previously returned in the last invocation of the callback, or initialValue, if supplied (see below).

*currentValue*
The current element being processed in the array.

*currentIndex (Optional)*
The index of the current element being processed in the array. Starts at index 0, if an initialValue is provided, and at index 1 otherwise.

*array (Optional)*
The array reduce() was called upon.

------------------------------------------------------------------------------------------------------------------------------------------------

**ES6**: EcmaScript 6

**What is it and how to use it **:
EcmaScript is not any scripting language instead a standard that Javascript is based upon. 
So, ES6 is a new version or new standard of Javascript.
ES6 brings many new feature like concept of **classes**, **template tags**, **arrow functions** etc.

### ES6 classes
A class is a template that you can use to create objects.


**Class declaration template**
```Javascript
class className = {
 
 constructor (parm1, param2, ...) { // <-- the constructor method is called when a new object is created using "new"
  // example:
  this.variable1 = param1; // <-- init some variables with params
  this.variable2 = param2;
  method
 }
 
 // Declare several methods for this class 
 method1 () {
  // add some behaviour for method 1
  // example:
  return this.variable1 + this.variable2;
 }
 
  method1 () {
  // add some behaviour for method 1
  // example:
  return this.variable1 + this.variable2;
 }
 
}
```

**Object creation**
To create an object from a class template, use the key word "New".

```Javascript
Ex: const myCar = new Car;
```


------------------------------------------------------------------------------------------------------------------------------------------------
**NodeJS**















