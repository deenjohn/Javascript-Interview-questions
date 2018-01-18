
### Hoisting
https://developer.mozilla.org/en-US/docs/Glossary/Hoisting

variable and function declarations are put into memory during the compile phase,
but stays exactly where you typed it in your coding.

1)

b();
console.log(a);

var a = 'Hello World!';

function b() {
    console.log('Called b!');
}


### Scope :

What is the output ?

1)
function a() {
    
    function b() {
        console.log(myVar);
    }
    
    b();
    var myVar = 2;   
}

var myVar = 1;
a();

2) 
function a() {
    
    function b() {
        console.log(myVar);
    }
    
    var myVar = 2; 
    b();  
}

var myVar = 1;
a();

3) 












