# InterviewJS

InterviewJS is a curated collection of essential JavaScript interview questions and answers designed to help developers prepare for technical interviews. Whether you're a junior developer looking to solidify your understanding of JavaScript concepts or an experienced engineer gearing up for a new job opportunity, this repository serves as a comprehensive resource to enhance your interview readiness.

## JAVASCRIPT INTERVIEW QUESTION

|QUESTION NUMBER|           QUESTIONS                       |
|---------------|-------------------------------------------|
|       1       | [What's Javascript]                       |
|---------------|-------------------------------------------|
|       2       |

# QUESTION ANSWER

## What's javascript?

Javascript is a synchronous single threaded programming language. Shychronous means it's execute line by line in a order.Single threaded means it's execute one statement at a time.

## What's variable?

Variable refer to certain memory location where we can store data and accesed throughout the execution of program

## What's variable declertion?

Variable declaration is a produre to allocate memory for the variable.

syntax:-

keyword variable_name

## What's variable assigment?

It's a way to assign a vaalue to that memory location for further access.
When we declare a variable but does not assign any value,In javascript,a special keyword store inside it.If we perfrom any mathematical operation then the result turns into NaN(Not a number).

## What's variable defiination?

It's a procedure where we do variable declaration and variable assignment at a same line

syntax:-

keyword variable_name=value;

## What's data-type?

Data type defines the type of data that means which type of data we can store inside the variable.

## What's the rules for variable?

There are few rule,that we concern about while we declaring the variable

1.Variable should be combination of $,_,a-z,A-Z,0-9 this character.

2.Variable name connot started with number.

3.Variable name is case sensitive.

4.Always use camalCase for declaring variable.

5.Javascript reserved keyword cannot use as variable name.

## What's strictly type and loosely type language?

Strictly type language are those language where we specify the data type impliclity while declaring the variable like java,c,cpp etc.

Loosely type langugae are those language where we don't have to specify any data type while declaring the variable.  like javascript,python etc.

## What's primitive data type and what's user defined datatype?

Primitive data type are those data type which is already available in programming language,user can use that data type. Like Number,Object in javascript.

Sometimes, primitive data type is not enough to define the type of data,for that reason user specify their own data type that's called user defined data type.

## How many primitive data type vailable in Javascript?

List of available data type in Javascript:-

1.Number(All kind of number interger,float etc)

2.String(All kind of character string)

3.Object

4.Boolean(boolean data that's can be true or false)

5.BigInt(For bigger integer)

6.Symbol

7.undefined

8.null

## What's reference data type and value type data type?

In the case of reference type the memory refernce store inside the variable in the case of value type the actual value store inside the variable.We will discuss it later.

-----------------------------------------------------------------------------------------

## What's string?

String is the combination of one or more character enclosed by single and double quotes.

Syntax for declaring string

var s="String";
var s1='string2';

## What's string indexing?

In javascript,every character in a string denoted by a special number called index,that's actually string indexing. Javascript follows the 0-based indexing that means first character of string always in 0th index and last character always in length of the string-1 index.

For example

var s="String";

Here indexing acts as follows

index           character
0---------------- S
1---------------- t
2---------------- r
3---------------- i
4---------------- n
5---------------- g

We can print the all character by using for loop.

for(let i=0; i<s.length; i++)
{
    console.log(s[i]);
}

##  How to find the length of the string?

To finding the length of the string we have a property of String object called length by using this length property we find the length of the string.The length poperty return a Number specify the length of the string.

var s="String";
s.length 

It will return 6.

## What's string immutability?

In javascript,String is immutable in nature that means after declaring a string we cannot update the value of the string without any assignment

Suppose we declare 

var s="String";

If I do 

s.toLowerCase();
console.log(s);

Now,we see in the console the same string so the string value does not updated.That's string immutability.

## How to convert number to string?

There's two ways to convert number to string

1.By adding a empty string.

var s=20;


