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
### Array Methods
``` javascript

shift(); // used to delete array element from start

push("Amazon"); // use to add element in the end of array.

pop();  // use to delete element from end.

toString(); // use to convert array into string.

let mergedcomp =comp.concat(comp2); // use to combine or merge two arrays together.

unshift("Amazon"); // use to add element in the starting of array.

let slicecomp = comp.slice(1, 3); // use to access the indexx element if wee enter last element 3 then output give index 2.

comp.splice(2, 0, "Ola"); // use to add element after the given index

comp.splice(2, 1); // use to delete the element after the given index 2.

comp.splice(2, 1, "Ola"); // use to replace the element after given idx 2.
