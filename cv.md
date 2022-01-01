# Habibov Ismail
## Junior Frontend Developer
### Contacts
#### Phone: +79780726024;
#### Email: ismailaga123@gmail.com
#### Telegram: @IsmailHab
#### LinkedIn: [My LinkedIn](https://www.linkedin.com/in/ismail-habibov-91980a204/)
---
## Briefly About Myself:
Hello everyone, I want to tell you a little about myself. Since childhood, I dreamed, like other children in the world, to operate toy cars. But unfortunately, my dreams were not destined to come true ...

Now I had the opportunity to fulfill my dream again. Today we can control the computers that run the world and this is very cool!
I want to become a Senior Software Engineer, and on my way I am ready to overcome all kinds of difficulties associated with studying and developing my own skills.

Just as I coped with the beginning in the field of IT, I believe that in sha Allah, I will achieve my goal!

---
## Skills

___HTML___
1. HTML5
2. Pug(jade)
3. Handlebars

___CSS___
1. Sass
2. SCSS

___JavaScript___
1. OOP
2. Vue (15%)
3. React(50%)
	Redux(thunk)
4. Svelte(10%)
   
___Node JS___
1. ExpressJS

___Git___
1. Github
2. Gitlab

___Other___
1. VScode
2. WebStorm

---
## Code Example from Code Wars
__Exclamation marks series: Put the exclamation marks and question marks on the balance - are they balanced?__

_Each exclamation mark's weight is 2; each question mark's weight is 3. Putting two strings left and right on the balance - are they balanced?_
_If the left side is more heavy, return "Left"; if the right side is more heavy, return "Right"; if they are balanced, return "Balance"._

```
const weightMap = {
  "!": 2,
  "?": 3,
}

function balance(left,right){
   let l = left.split("").map(e => weightMap[e]).reduce((a, b) => a + b);
   let r = right.split("").map(e => weightMap[e]).reduce((a, b) => a + b);
   if (r == l)
      return "Balance"
   else if (r > l)
      return "Right"
   else
      return "Left"
}
```