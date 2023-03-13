![photo](photo.png "Мое фото")
## Sergey Grebel
engineer for commissioning and adjustment of microprocessor systems of railway automation
****

### Contact
- **Email:** _grebelsergey@mail.ru_
- **Discord:** _Serdg#1847_

****

### About me
I am an engineer for microprocessor-based railway automation systems. I am engaged in the launch and adjustment of the system we are developing at the stations of the railway and industrial transport.

****

### Skills
I am at the beginning of my journey to learn php, js, html and css

****

### Code example
*Write a function that counts how many different ways you can make change for an amount of money, given an array of coin denominations.*
```
function countChange(money, coins, flag = NaN) {
  if (isNaN(flag)) {coins.sort((a, b) => a - b)}
  flag = flag || 1;
  let counts = 0;
  if (money < 0 || coins.length == 0) {
    return counts;
  }
  if (money == 0) {
    return counts += 1;
  }
  let coinsPop = coins.slice(0);
  coinsPop.pop();
  return countChange(money - coins[coins.length - 1], coins, flag) + countChange(money, coinsPop, flag);
}
```

****

### Experience
Learn Web Developer
[cssBayan](https://gserdg.github.io/cssBayan/cssBayan/index.html)

****

### Education
Saint Petersburg State Railway Transport Universyty
Direction: computer systems in automatics and telemechanics

### English level
 A2