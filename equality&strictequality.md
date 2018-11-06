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
  if (val == '10') { 
    return "Equal";
  }
  return "Not Equal";
}

testStrict(10);

===return equal because '10' is equal to 10

// Setup
function testStrict(val) {
  if (val === 7) { 
    return "Equal";
  }
  return "Not Equal";
}


testStrict('7');
===return not equal beacuase 7 is different from '7'
