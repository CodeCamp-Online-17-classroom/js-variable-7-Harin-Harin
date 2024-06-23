# js-lab-7
### Lab7 DataTypes&Variable: console.log
- จงหาผลลัพธ์ในบรรทัดคำสั่ง console.log ทั้งหมด
- หริณ มาเบ้า มิก
```shell
- ผลลัพท์ที่ได้คือ
number is 2
app.js:4 result is 4
app.js:5 I live in Thailand
app.js:6 I live in Thailand, Asia
app.js:7 I live in Thailand, Asia
app.js:8 I live in country, continent
```
``` JavaScript
const country = 'Thailand';
const continent = 'Asia';
console.log(`number is ${2}`); //number is ...
console.log(`result is ${1 + 3}`);
console.log(`I live in ${country}`);
console.log(`I live in ${country}, ${continent}`);
console.log(`I live in ${country + ', ' + continent}`);
console.log(`I live in ${'country, continent'}`);"
```
