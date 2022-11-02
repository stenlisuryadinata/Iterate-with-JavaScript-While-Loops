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

/*
for(let i=102; i > 27; i -=3 ) {
    console.log(i);
  }
*/
/*
let arr= [ ]; 
for (i=3; i < 12; i++){
  arr.push(i);
}
console.log(arr);
*/
/*
let myArr = [3, 10, 9, 5, 2, 11, 7, 15, 12, 4, 1, 13, 6, 14, 8]; 

for(i = 0; i < myArr.length; i++){
  if(myArr[i]>=3 && myArr[i]<=7){
    console.log(myArr[i]);
  }
}
console.log(myArr);
*/
/*
let myArr = [3, 10, 9, 5, 2, 11, 7, 15, 12, 4, 1, 13, 6, 14, 8]; 

for(i = 0; i < myArr.length; i++){
  if(myArr[i] < 3 || myArr[i]>7){
    console.log(myArr[i]); 
  }
}
console.log(myArr);
*/
/*
let myVar = 'microverse';
console.log(myVar.substring(0,5));
console.log(myVar.substring(5));
*/
/*
let myArr = [1,2,3,4,5,6,7,8,9,10,13]; 

if(myArr.includes(13) === true){
  console.log("Found it!");
}else {
  console.log("Not Found"); 
}
*/

/*
let myArr = [1,2,3,4,5,6,7,8,9,10]

let num = []; 
for(i=0; i<myArr.length; i++){
  if(myArr[i]>3 && myArr[i]<10){
    num.push(myArr[i]);
  }
}
console.log(num);
*/

/*
let bigarr = [[1,2,3,4], [2,3], [9,8,7,7,7]];
for(i=0;i<bigarr.length;i++){
  console.log(bigarr[i]);
  for(j=0; j<bigarr[i].length;j++){
    console.log(bigarr[i][j]);
    
  }
}

let myArr = [[1, 2, 3], [4, 5, 6],[7, 8, 9]];
for(i=myArr.length-1;i>=0;i--){
  console.log(myArr[i]);
  for(j=myArr[i].length-1; j>=0; j--){
    console.log(myArr[i][j])
    
  }
    
}

*/

