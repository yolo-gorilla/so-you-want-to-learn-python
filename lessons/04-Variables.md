## 04- Variables
### Variables, types and assigments 


Now that you know how to write and run a simple hello world program, we will be diving into learning some of the meat and potatoes of the python programing language. 

#### Variables 

Variables are placeholders for a value in your computer program. They usually can be set and updated on the fly by your computer program. 
They usually look something like this :

``` x = 5 ``` or ``` name = "Alice" ```

The format for setting a variable is:
```[variable name] "=" [variable value]```
Your variable name can't have spaces in it and traditionally uses camel case format : "variableName" 

The value you assign can be letters, names or numbers. The different types of values that a variable can be is called **Variable Types** 

#### Variable Types

Variable types in python are :
- Text:
  - str (string)  
- Numeric Types:
  - int (interger)
  - float (float)
  - complex  (complex)
- Sequence Types:
  - list
  - tuple
  - range
- Mapping Type:
  - dict
- Set Types:
  - set
  - frozenset
- Boolean Types:
  - bool 
- Binary Types:
  - bytes
  - bytearray
  - memoryview
- None Type:
  - NoneType 

:cold_sweat: Whoah that is a lot isn't it? 

Well don't worry about learning them all at once. That would be really hard and frustrating for a beginer.
For this course we will focused on the most used variable types. These variable types are the ones that you are most often be dealing with. 

#### setting Value 

In python the variable type is automatically set when you set the variable. This is because python is a dyunacmically typed language. It is flexible enough to know when you put a numbe in a variable that that number is an int. 

so when setting a variable value :
```x = 20``` is an interger or "int" for short

```x = 20.5 ``` is a float 

```x = "20" ``` is a string

#### Ints 
Intergers are a whole number (both postive and negative) including "0". 

#### Float
Floats are postive or negative real numbers. So think of decimals. 
#### Strings 
Strings are text. These are usually set with quotiation marks ```"variable value" ``` or ``` 'variable value' ```. 
#### Booleans 
Booleans are true or false values. They are very helpful when dealing with comparison operators (don't worry that is a later chapter). 


#### Type casting variables
You can't add a text string to an int. This is because types in python can often only calculate with other types of the same parent type (so numeric with numeric). 

An example, This will give you errors when you try to run a python script. 
```
#This causes errors:
a = 5
b = "2"
sum = a + b 
```

What you have to do is "type cast" your variable  to a numeric variable. Typecasting is coverting one type to a different type. 

```
a = 5
b = "2"
#since b is a string we will change b to an int
b = int(b)
sum = a + b 
```
That is all there is to typecasting. You can even do it on the fly. Below are the ways to typecast different variable types:
Interger - int(x)

Float - float(x)

String - str(x)

When you are not sure what kind of value a variable is you can check with the "type()" function:
```
a = 5
print(type(a))
#will print: <class 'int'>
b = 10.5
print(type(b))
# will print: <class 'float'>
c = "100"
print(type(c))
# will print: <class 'str'>

```

You now know the basics of python variables. 


