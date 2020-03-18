# javascript_es6_new_features

# Javascript let
## The let statement allows you to declare a variable with block scope.

var x = 10;

// Here x is 10

{ 
  
 let x = 2;

  // Here x is 2

}

// Here x is 10

## let is used for reassign value.

let x = 2;

// Here x is 2

{
  x = 3;
}

// Here x is 3

# JavaScript const

## The const statement allows you to declare a constant (a JavaScript variable with a constant value).

## Constants are similar to let variables, except that the value cannot be changed.
var x = 10;

// Here x is 10

{ 
  
 const x = 2;
 
 // Here x is 2

}

// Here x is 10

## const is used for value never changed

const x = 2;

x = 3;      // This will give an error

x = x + 10;   // This will also give an error


## Javascript Arrow function
// ES5
var a = function(a, b) {
   return a + b;
}

// ES6
const a = (a, b) => a + b;
