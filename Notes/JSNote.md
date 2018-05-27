<a name="top"></a>  
# JavaScript Notes  

<[JavaScript Basics](#basics)>  

<a name="basics"></a>  
## JavaScript Basics  
[Top](top) 

#### Console  

Console is a tool to display output.
*console.log()* is used to print.

#### Data type  

There are four primitive data types.  
* String  
* Numbers  
* Booleans  
* Null  - represents the absence of value  

#### Properties  

Eevery instances(individual case(or bject) of a data type) has additional information attached to it.  
EX)  
* String has *length*.  
It can be retrieved by appending with a period and the property name.  

	console.log("Hello World".length);  

// It will return  
// 12

#### Built-in Methods  

Functions that's built-in. Remember some basic ones.  

	.toUpperCase()  

Returns a strign in all capital letters.  

	.startsWith("parameter")  

Return boolean if the instance matches with the given parameter.  

	.trim()  

It will removes whitespace from both ends of a string.  

#### Libraries  

Libraries contain methods that you can call without creating an instance.  
Call method name appending the library name.  

	console.log(Math.random());  

It will return random value between 0 and 1 and it will be decimals.  

	console.log(Math.random() * 100);  

Returns random value between 0 and 100 with decimals.  

	console.log(Math.floor(Math.random() * 50));  

Returns random whole number between 0 and 100.  

	Math.ceil(x)  

Returns the smallest integer greater than or equal to a given number.  

	Number.isInteger()  

Determine wheather the passed value is an integer. Returns boolean.  
