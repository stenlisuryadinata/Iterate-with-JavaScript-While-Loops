# Iterate-with-JavaScript-While-Loops


// Setup
const myArray = [];

// Only change code below this line
let i = 5;

while (i >= 0) {
  myArray.push(i);
  i--;
}

console.log(myArray);


Output: 

[ 5, 4, 3, 2, 1, 0 ]
Hint: hit control+c anytime to enter REPL.


Iterate with JavaScript For Loops

// Setup
const myArray = [];


// Only change code below this line
for (let i = 1; i < 6; i++) {
  myArray.push(i);
}

console.log(myArray);


Count Backwards With a For Loop

// Setup
const myArray = [];

// Only change code below this line
for (let i = 9; i > 0; i -= 2) {
  myArray.push(i);
}

console.log(myArray);

Iterate Through an Array with a For Loop


// Setup
const myArr = [2, 3, 4, 5, 6];
let total = 0; 
// Only change code below this line
for (let i = 0; i < myArr.length; i++) {
   
   total = total + myArr[i]; 
   console.log(total);
}


