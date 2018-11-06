# comparison-opertators
these are!

= assignment operator
== equality operator
=== strict equality operator

1   ==  1     //true
1   ==  2     //false
1   == '1'    //true
"3" ==  3     //true
3 === 3       // true
3 === '3'     // false


// Setup equality operator "=="
function testStrict(val) {
  if (val == 7) { 
    return "Equal";
  }
  return "Not Equal";
}

testStrict(10);

return not equal because 7 is not equal to 10
