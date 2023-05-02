### what is function?
***function*** is used to perform particuller task

### what is variable?
***variable*** is used to store the value.


### diffrent between let var const?
##### scope
***let*** is blocked scope and ***var*** is globle scope.

##### decalre
we can't redecalre with ***let*** but we can redecalre with ***var***.

##### const
scope of ***const*** same as ***let*** but we can not change the value.

### arrowfunction vs nrmal function
1. we dont need to add function keyword with arrow function.
2. syntex is shorter then normal function.
3. we use => to declare arrow function 

### For loop

```
const n = 5;

for(let i = 0; i < n; i++) {
    console.log(`anil`);
}

result=======>>>>>>>>

"anil"
"anil"
"anil"
"anil"
"anil"

```


 ### HTML , CSS
Higher order functions...
-->map , reduce, filter, forEach
-->type script (class , types ,https://www.youtube.com/watch?v=gKZ5usVG47U)
-->import , export
---> local Storage
---> jwt (only study)

#### Angular --->
 ### componet
 ### forms (Reactive form , Template driven)
 ### Services  
 ### HttpClinent (get , post, delete, put)
 ### Routing(Can active)
 ### Lazy Loading
 ### interpolation, two way binding, event binding
 ### *ngIF , * ngFor
 ### project 
 
 ### Array remove second last value and sum of array
 
 let num=[18,28,27,8]

num.splice(-2,1)

let abc=num.reduce((pre,curnt)=> pre+curnt)
console.log(abc)

### Object remove second last value and sum of object

let num = {
  "a": 18,
  "b": 28,
  "c": 27,
  "d": 8
}
delete num.c

let abc = Object.values(num)

let xyz = abc.reduce((pre, curnt) => pre + curnt)

console.log(xyz)


