# javascript-reference
a collection of javascript notes

## Varibles
###### var, let, const, scope

## Functions

## Conditionals
  * 'if'
  * 'if else'
  * 'switch statement'
  

## Loops
 #### 'for loop'
 #### 'while loop'
 #### 'do while loop'
 #### 'for in loop' (for objects only)
  ```

  var shanghai = {
  population: 14.35e6,
  longitude: '31.2000 N',
  latitude: '121.5000 E',
  country: 'CHN'
 };
   //prints out object values
 for ( var props in shanghai){
  console.log(shanghai[props]);
 };
   //prints out object properties
  for ( var props in shanghai){
  console.log(props);
 };
 
```

## Data Structures: Arrays, Objects, 2D arrays
 #### 'Arrays' : They are like a shopping list
 #### 'Objects': Similar to a collection of variables
  
## ES6 Creating Variables (var should be avoided)
 ### 'Const' :  (block level scoping) once you create a variable it cannot be changed, prevent the value from being reassigned
 #### use case (tax rates, product prices, dimensions of interface, 
 ```const pi = 3.14;```
### 'Let' :  prevents errors when using for loops
### Summary: Use 'const' when assigning variables and use 'let' when needed to re-assign variables.

