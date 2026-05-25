# TEMPLATE LITREALS

this is a special type of string created with backticks (`) We dont use (,) we use $ to access the variables 

without this we write like                                                                                   


### BEFORE - 
``` javascript
let name = "Mehra"
         let age = 25;
          console.log ("my name is " , name , "and my age is ", age);
```
- where we using , , again and again but when we use #TEMPLATE LITREALS
we use like

### AFTER
``` javascript                - 
 let name = "Mehra"
 let age = 25;
 console.log (`my name is ${name} and my age is ${age}`);
 console.log(typeof name);
```

# STRING INTERPOLATION 
${expresions or variable}  this is called string interpolation

# ARRAYS
Arrays is mutable

we are using looping to acces and make changes in each idx of array 

``` javascrpt
let arr = [ 250, 300, 350, 400, 450 ];
for (let i =0; i< arr.length; i++){
    let offer = arr[i] /10;
    arr[i] -= offer;
     console.log(`The offer for ${arr[i]} is ${offer}`);
}
```
