# Pavel Barysevich-Bleyaniuk
![photo of Pavel Barysevich-Bleyaniuk](/rsschool-cv/images/pavel_barysevich-bleyaniuk.jpg)

![telegram logo](/rsschool-cv/images/icons/Telegram_Messenger.png) **@blejaniuk**

![discord logo](/rsschool-cv/images/icons/icon_discord.png) **paviel3730**

[![github logo](/rsschool-cv/images/icons/icon_github.png) **Paviel-Barysevich**](https://github.com/Paviel-Barysevich/)

I like learning and finding out something new. My goal is to become a software engineer. I want to get new experience in developing software products.

## My hard skills:
 * Java Script;
 * HTML / CSS;
 * Git;
 * Dev-tools, Visual Studio Code.

## Code example:

### [Task :](https://www.codewars.com/kata/5a946d9fba1bb5135100007c)

_Given a List [ ] of n integers , find minimum number to be inserted in a list, so that sum of all elements of list should equal the closest prime number ._

### Solution:

```javascript
function minimumNumber(numbers){
  let sum = numbers.reduce((acc, number) => acc + number, 0);
  let isPrime = sum;

  outer:
  for (let i = 2; i <= isPrime ** (1 / 2); i++) {
    if (isPrime % i === 0) {
      isPrime++;
      i = 1;
      continue outer;
    } else {
      continue;
    }
  }

  return isPrime - sum;
}
```
## Education

* [Hrodna State Agrarian University](https://www.ggau.by/);
* [RS School](https://rs.school/).

## English

_Pre-Intermediate._