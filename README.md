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



