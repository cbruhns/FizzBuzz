<h1>FizzBuzz</h1>
<p>A common loop exersise to test logic based output. "Please output every number on the page between one and 
one-hundred. If a number is a multiple of three, instead of the number, output the word "Fizz." If the number 
is a multiple of five, instead of the number, print the word "Buzz." If the number is a multiple of both three 
and five, output the word "FizzBuzz.""</p>

``` JavaScript
for( var i=1 ; i<101 ; i++ ){
  var f = i%3 == 0, b = i%5 == 0;
  document.write( f ? b ? "FizzBuzz" : "Fizz" : b ? "Buzz" : i," <br />");
}
```
