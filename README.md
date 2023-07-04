# day1
celebal js

// variables

//var
//var a=1
//var b=2
//var c=a+b
//console.log(c)

//let
//let x=1
//let y=2
//let z=x+y
//console.log(x,y,z)

//const
//const x=5
//const y=6
//const z=x+y
//console.log(x,y,z)

//rules of decleration of the the varibale
//letter,digit,underscore,dollar sign

//let name ='kum'
//let $name = 'kum'
//let _name = 'kum'
//let 1name = 'kum'   (it is not right bcz can't start with number)

//var city = 'jaipur'
//var city = 'delhi'
//(we can use same variable in "var" to repersent something like city)

//let country = 'india'
//let country = 'india' 
//(we can't use same variable in "let" to repersent something like country . it will give us error. so we can declair it as in function...)
//function fun (){
//    let country = 'china'
//}

//let d ='temp'
//let D ='temp'

//Operators

// 1 Arithmetic Operators 
//add
//sub
//mul
//div
//mod
//increment
//decrement

// let x = 5+5
// let y = 10-5
// let z = x*y
// let w = x/y
// let a = x%y
// a++;
// z--;
// console.log(x,y,z,w,a,z)

// 2 Assignment Operator

//assignment: =
//addition assignment: +=
//subtract assignment: -=
//multiplication assignment: *=
//division assignment: /=
//modulus assignment: %=

// let x=5
// x+=2
// x-=1
// x*=3
// x/=2
// x%=2


//comparidon operator

//equal to: ==
//not equal to: !=
//strict equal to: ===
//strict noy equal to: !==
//grater than: >
//less than: <

//console.log(5=='5')
//console.log(5==='5')

//Logical Operator
//And: &&
//Or: ||
//not: !

//console.log(5=='5'&&4==4)
//console.log(5=='5'||4==4)


//String Operator

// let temp ='i am temp'
// let temp2 ='i am temp2'
// console.log(temp+temp2)

//Conditional Operator
//conditional? exp1: exp2

//let tem3 = 5>4 ? 5: 4;
//console.log(tem3)

//Data Types

// primitive data type 
// Number
// string
// Boolean
// null
// undefined

// let age = 25
// let name = 'kum'
// let isIndian = false
// let person = {
//     name: 'kum',
//     age: 20,
// }
// let numbers = [1,2,3]
// console.log(typeof age)
// console.log(typeof name)
// console.log(typeof isIndian)
// console.log(typeof person)


//Conditional Statement

//if
//else if
//else 
//switch

// if(5>6){
//     console.log('5')
// }
// else if(5==6){
//     console.log('6')
// }
// else{
//     console.log('greater than 6')
// }


//switch
// let value = 2

// switch(value){

//     case 0:
//         console.log(0)
//         break
//     case "0":
//         console.log(zero)    
//     case "1":
//         console.log('one')

//      default:
//         console.log('unknown value')   
// }

//For loop
// for(let i=0; i<5; i+=2){
//     console.log(i)
// }

// const person = {
//     fName: 'kum',
//     lName: 'Doe',
//     age: 20 
// }

// for(let x in person){
//   // console.log(x)
//   //console.log(person[x])
//   console.log(x, ':' ,person[x])
// }

//for of

// const car = ["BMW", "Volvo", "Mini"]

// let data=""
// for(let x of cars){
//     data+=x
// }
// console.log(data)

//For each 
const arr= [1,2,3,4]
let sum=0

arr.forEach(addition)

function addition(value){
    sum+=value
}
console.log(sum)


OUTPUT:
![image](https://github.com/kukumchouhan/day1/assets/110415227/f8cb801d-4583-4125-9778-bfa4165a044c)


day2:
//Functions in JavaScript

// let result = mul(5,10)
// console.log(result)
// function mul(a,b){
//     return a*b
// }    

// let result = mul(5,10)
// console.log(result)
// function mul(a,b,c=0){
//     return a*b*c
// }  


//Arrow Function
// multiplication =(a,b)=>{
//     return a*b
// }

// console.log(multiplication(5,10))

// multiplication =(a,b)=>
//       a*b

// console.log(multiplication(5,10))

//Spread operator
// const arr = [1,2,3,4,5]
// const arr1 = [...arr]
// console.log(arr1)

// const arr = [1,2,3,4,5]
// const arr1 = [...arr]
// const[one,...rest] = arr
// console.log(arr,arr1,one,rest)

// File System:-(CRUD Operation)
// 1. create file:- (a) Append
//                  (b) Open
//                  (c) write
// 2. Read file (Read File())
// 3. update File (a) Append
//                (b) write 
// 4. Delete (unlink())

// var fs = require('fs');
// //Append File
// fs.appendFile('file.txt','this is file1',(err)=>{
//     if(err) throw err
//      console.log('file1 created')
// })

// // write file
// fs.writeFile('file2.txt','this is file2',(err)=>{
//             if(err) throw err
//             console.log('file2 is created')
// })

// // open file
// fs.open('file3.txt','w',(err)=>{
//     if(err) throw err
//     console.log('file3 created!')
// })

//Read =>readFile()

// fs.readFile('file1.text', 'utf-8',(err,data)=>{
//     if (err) throw err

//     console.log(data)
// })

// //update file 
// appendFile()
// var fs = require('fs');
// fs.appendFile('file.txt','file updated',(err)=>{
//     if(err) throw err
//     console.log('fileupdateed!')
// })

//writeFile()
// var fs = require('fs');
//  fs.appendFile('file2.txt','file2 updated',(err)=>{
//      if(err) throw err
//      console.log('file2 updateed!')
//  })

//Delete (unlink)
// var fs = require('fs');
// fs.unlink('file3.txt',(err)=>{
//     if(err) throw err
//     console.log('file3 is deleted')
// })

//Rename
var fs = require('fs')
fs.rename('file.txt','renamed file.txt',(err)=>{
if (err) throw err
console.log('file is renamed')
})
OUTPUT:
![image](https://github.com/kukumchouhan/day1/assets/110415227/40c1ad30-164f-4395-90f6-4ffbd8d11ae0)

![image](https://github.com/kukumchouhan/day1/assets/110415227/e4d48b2e-849c-404b-a9e7-3b5af52847e9)

![image](https://github.com/kukumchouhan/day1/assets/110415227/f5bd1b1a-e9e9-46f1-a975-b130b8c12040)

![image](https://github.com/kukumchouhan/day1/assets/110415227/a8641e82-d846-45c2-8b1e-af6685a93e9b)

![image](https://github.com/kukumchouhan/day1/assets/110415227/a036271a-12f7-4490-9c4e-ea972862446e)

![image](https://github.com/kukumchouhan/day1/assets/110415227/882e9496-6c09-4074-a0b3-c00259e8a312)

![image](https://github.com/kukumchouhan/day1/assets/110415227/c25da9ec-7614-4c1c-9463-2996b94fd9de)


![image](https://github.com/kukumchouhan/day1/assets/110415227/be934fa9-f3f5-48dd-80fa-fbc61725ccfb)

![image](https://github.com/kukumchouhan/day1/assets/110415227/8363ce11-1659-4e38-aecf-4e0f6d6752f0)




