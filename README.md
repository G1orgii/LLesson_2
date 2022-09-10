# LLesson_2
// 1.
// let x = 0;

// function sum(...numbers){
//     for(let i = 0; i<numbers.length; i++){
//         if(numbers[i]>=0){
//             x += numbers[i];
//         }
//     }
//     console.log(x);
// }
// sum(2, -9, 5, 11, -30, 100, -8, -11, 8);



// 2.
// let x = 0;

// function sum(...numbers){
//     for (let i=0; i<numbers.length; i++ ){
//         x += numbers[i];
//     }
//     console.log(x);
// }

// sum(10, 50, 6, 7, 8, 11, 6, 3, 9);



// 3. 
// let user = {
//     firstname:"giorgi", 
//     lastname:"saakadze",
//     age:32,
//     isloggedin:true,
// }

// function start(){
//     if(user.isloggedin == true){
//         console.log(user.firstname + " " + user.lastname);
//     }else{
//         console.log("false")
//     }
// }
// start();


// 4.
// let max = (...numbers) =>{
//     console.log(Math.max(...numbers));
// }
// max(20, 30, 40, 50);


// 5.
// let array = [1, 2, 4, 10, 34, 5, 7, 87];
// for(let item of array){
//     if(item>0 && item<10){
//         console.log(item);
//     }
// }

// 6.
// let numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]

// for(let item of numbers){
//     if(item == 5){
//         break
//     }
//     console.log(item);
// }
