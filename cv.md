# Pavel Barysevich-Bleyaniuk
![cvPhoto](images/myPhotoForCV.jpg "My photo for CV")

---

## My contacts
__Phone:__ +375(33)6\*\*\*\*\*2

__E-mail:__ pavelmessage@gmail.com

__Discord:__ Pavieł #3730

## About me
My goal is to become a front-end developer and achieve a high professional level.

I pursuit to learn *new knowledge* and *information*.

## Skills
1. HTML, CSS.
2. JavaScript.

## Code example
A task from [codewars.com](https://www.codewars.com/kata/517abf86da9663f1d2000003/javascript "Convert string to camel case
"): *Complete the method/function so that it converts dash/underscore delimited words into camel casing. The first word within the output should be capitalized only if the original word was capitalized (known as Upper Camel Case, also often referred to as Pascal case). The next words should be always capitalized.*

__Examples__

"the-stealth-warrior" __gets converted to__ "theStealthWarrior"

"The_Stealth_Warrior" __gets converted to__ "TheStealthWarrior"

__My solution__

```
function toCamelCase(str){
  let arr = [];
if (str.includes('-')) {
arr = str.split('-');
} else {
arr = str.split('_');
}
let newArr = [arr[0]];
for (let i = 1; i < arr.length; i++) {
let subArr = arr[i].split('');
subArr[0] = subArr[0].toUpperCase();
let subStr = subArr.join('');
newArr.push(subStr);
}
let camelStr = newArr.join('');
return camelStr;
}
```

## Education
Hrodna State Agrarian University.

__RS-School.__ Front-end (JavaScript) course.

## English
*Pre-Intermediate (A2).*
