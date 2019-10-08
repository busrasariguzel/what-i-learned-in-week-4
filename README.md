# `What I learned In week 4`

## `Booleans`
Booleans are type of javascript data that takes  only two values: true or false.
* `!`= not 
* `===` equals
* `!==` not equal to
* `>=` greater and equal to
* `<=` less than and equal to 
* `||` or
* `&&` and

some examples of booleans 
function both(condition1, condition2) {
  return condition1 && condition2;
  

}

function either(condition1, condition2) {
  return condition1 || condition2;
}

function neither(condition1, condition2) {
  return !condition1 && !condition2;
  
}

---
## `If Statements`




---

## `Else / if`
* Else can only come after if.
  
if (temp>35){
    return "It's very hot!"
  }
  else if (temp>18 && temp<35){
    return "Such a nice weather!"
  }
  Else if (temp<18){
    return "It's a bit chilly!"}
  Else if (temp<0){
    return "Don't go out!"
  }
  



---

## `Binary operations`
===
!= %


---

## `The ternary operator`

* Takes 3 values and resolves in one value.
* Short version of else if statement if there are only 2 possible outcomes.
  
Example: 

case 'istanbul':
    return temperatureType === 'fahrenheit' ? 'Istanbul 71F' : 'Istanbul 22C';
---
## `Switch`
* Similar to else if statement
* Easier to read
  
  Example :
   
  Switch(city){
    case 'istanbul':
      return temperatureType === 'fahrenheit' ? 'Istanbul 71F' : 'Istanbul 22C';
    case 'london':
      return temperatureType === 'fahrenheit' ? 'London 55F' : 'London 13C'; }


---
## `Iffy`

I enjoyed this project a lot because we could pick our own topic, which allowed us to be creative. My project tells weather of different cities around the world, both in celsius and fahrenheit. If you type "istanbul celsius" you would get the weather in istanbul in celsius. If you type "Istanbul fahrenheit" you will get that number converted to fahrenheit. I added around 10 cities to make it global. I used *switch* for my code. It was very helpful for me to practice switch and ternary operations. I also practiced console.log in this project. Overall, I liked it. It was challenging but fun! I like projects that allows us to be creative.
---