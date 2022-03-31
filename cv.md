# Shovkatova Sitora Shovkatovna
### Contacts
**Phone:**+(998) 93 504 01 65<br>
**Telegram:**@rikkimonti96<br>
**Email:** rikkimonti@gmail.com
### About me
*I'm 25 years old. At the moment I have been studying at academy IT STEP for almost 1.5 years. I love making games and dream of starting my own company like RIOT GAME and making my own games in the future.*
### Skills
* HTML5, CSS3
* JavaScript Basics
* Git, GitHub
* VS Code, IntelliJ IDEA
* PHP(Laravel)
* C/C++, C#
* MySQL
* Unity
### Code examples
*Request a date (day, month, year) and output the following her date. Consider the possibility of moving to the next month, year, and leap year.*

```
let date = prompt("Enter date [dd.mm.yy]:");

date = date.split('.');

let oldDate = new Date(date[2], date[1] - 1, date[0]);

oldDate.setDate(oldDate.getDate() + 1);

alert(oldDate);
``` 