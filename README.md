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

/*
let bigarr = [];

let ext =9; 
for(i=0;i<3;i++){
  //bigarr.push([]);
  let little = []; 
  for(j=0;j<3; j++){
    little.push(ext);
    ext--;
  }
  bigarr.push(little);
}
console.log(bigarr)
*/

/*

function numbers(a,b){
  console.log(a*b);
}

numbers(3,4);

function message(name){
  console.log("Hello ",name)
  
}

message('Oscar');
message('Clinton');
message('Lina');
message('Triad');

*/
/*
function sum(myArr){
  let output = [];
  for(i=0; i<myArr.length; i++ ){
    output.push(myArr[i]+1)
  }
  return output;
}

let result = sum([1,2,3,4]);
console.log(result); 
*/
/*
function sum(myArr){
  let output = [];
  for(i=0; i<myArr.length; i++ ){
    output.push(myArr[i]*5)
  }
  return output;
}

let result = sum([1,2,3,4]);
console.log(result); 
*/
/*
function reverse(arr){
  let output = []; 
  for(i=arr.length-1; i>=0; i--){
    output.push(arr[i]);
  }
  return output;
}

let result2 = reverse([1,2,3,4,5,6,7,8,9]);
console.log(result2);
*/
/*
let arr = [1,2,3,4]; 


function reverse(arr){
  let output =[];
  for(i=arr.length-1; i>=0; i--){
    if(arr[i] === 1 ) {
      output.push('one')
    }
    if(arr[i] === 2 ) {
      output.push('two')
    }
    if(arr[i] === 3 ) {
      output.push('three')
    }
    if(arr[i] === 4 ) {
      output.push('four')
    }
    //output.pop(arr[i]);
    //output.push(arr[i]);
    
  }
  return output
}

let result= reverse([1,2,1,2]);
console.log(result);
*/
/*
function sumAll(arr){
  let first = arr[0]; 
  let last = arr[1]; 

  if(first >last){
    first = arr[1];
    last = arr[0];
  }

  let output = 0; 
  for(i=first; i <=last; i++){
    //console.log(i);
    output += i;
  }
  return output;
}

let result = sumAll([1,4]); 

console.log(result);

let result2 = sumAll([4,1]); 

console.log(result2);

*/
/*
function convertCtoF(celsius) {
  let fahrenheit;
  

  fahrenheit = (celsius * (9/5))+ 32;
  return fahrenheit;
}

let result = convertCtoF(30);
console.log(result);
*/
/*
function reverseString(str) {
  
  let reversedStr = "";
  for (let i = str.length - 1; i >= 0; i--) {
    reversedStr += str[i];
  }
  return reversedStr;
}


reverseString("hello");

*/

/*
function factorialize(num) {
  
let product = 1;
  for(let i =2; i<=num; i++){
    
    product *= i;
  }

  return product;
}

let result = factorialize(5);
console.log(result); 
*/
/*

function truncateString(str, num) {
  if (str.length>num){
    return str.slice(0,num)+"...";
  }else {
    return str;

  }
}

let result = truncateString("A-tisket a-tasket A green and yellow basket", 8);

console.log(result)

*/
/*
function getIndexToIns(arr, num) {
  console.log(arr.sort((a,b) => a-b)); 

  for(let i = 0; i<arr.length; i++){
    //console.log(arr[i]);
    if(arr[i]>=num) return i;
    
  }
  return arr.length;
}

let result = getIndexToIns([20, 3, 5], 19);
console.log(result);

*/
/*
function chunkArrayInGroups(arr, size) {
  
  let temp =[];
  let result =[];
  for(let i=0; i<arr.length; i++){
    if(i % size !== size-1) temp.push(arr[i]);
    else {
      temp.push(arr[i]);
      result.push(temp);
      temp=[];
    }
  }
  if (temp.length !== 0) result.push(temp);
  return result;

}

let results = chunkArrayInGroups(["a", "b", "c", "d"], 2);
console.log(results);

*/
/*
//SALES BY MATCH Hackerrank 
function sockMerchant(n, arr){
  let pairs = 0; 
  let search = new Set(); 
  for(const sock of arr){
    if (search.has(sock)){
      pairs ++;
      search.delete(sock);
    } else {
      console.log(search.add(sock));
    }
  }
  return pairs;
}
let result = sockMerchant(9,[10,20,20,10,10,30,50,10,20]);
console.log(result);
*/
/*
//SALES BY MATCH Hackerrank 
function sockMerchant(n,ar){
  let pairs = 0; 
  let socks = {};
  ar.forEach((sock) => {
    //console.log(sock)
    if(!socks[sock]){
      socks[sock] = 0; 
    }

    socks[sock] = socks[sock] + 1;
    
    if(!(socks[sock] %2)){
      
      pairs = pairs + 1;
      
    }
    });
  return pairs;
}

let result = sockMerchant(9,[10,20,20,10,10,30,50,10,20]);
console.log(result); 
*/
/*

//DRAWING BOOK Hackerrank

function pageCount(n,p) {
  let totalPageTurnCountFromFront = n/2; 
  let targetPageTurnCountFromFront = p/2;
  let targetPageTurnCountFromBack = totalPageTurnCountFromFront 
 - targetPageTurnCountFromFront;

  return Math.min(targetPageTurnCountFromFront,targetPageTurnCountFromBack);
};

let result = pageCount(5,4);
console.log(result);
*/
/*
//DRAWING BOOK Hackerrank 

function pageCount(n,p) {
  
  let totalPage = n/2; 
    let frontCount = Math.floor(p/2); 
    let backCount = Math.floor(totalPage - frontCount); 
    return Math.min(frontCount, backCount);
};

let result = pageCount(5,4);
console.log(result);

*/


