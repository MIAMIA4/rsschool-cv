![foto](https://i.ibb.co/vkyG9kg/Photo-2023-03-04-19-19-47.jpg)


# dr. Ilya Markin

## Junior Frontend Developer

**Contact information:**

Phone: +7(915)455-34-14  
E-mail: 19962191a@gmail.com  
[Telegram](+79154553414)  
[codewars](https://www.codewars.com/users/MIAMIA4)  

----

**Briefly About Myself:**

Motivated and skilled junior frontend developer with a strong interest in developing software products that can improve healthcare outcomes. Experienced in building responsive web applications and working in collaborative environments. Committed to using my skills and knowledge to make a positive impact on society.

---
**Skills and Proficiency:**
* HTML5, CSS3
* Sass, SCSS
* JavaScript Basics
* Git, GitHub
* VS Code
* Figma

---
**Code example:**

DESCRIPTION:
Your task is to create a function that will take an integer and return the result of the look-and-say function on that integer. This should be a general function that takes as input any positive integer, and returns an integer; inputs are not limited to the sequence which starts with "1".

Conway's Look-and-say sequence goes like this:

Start with a number.
Look at the number, and group consecutive digits together.
For each digit group, say the number of digits, then the digit itself.
This can be repeated on its result to generate the sequence.

For example:

Start with 1.
There is one 1 --> 11
Start with 11. There are two 1 digits --> 21
Start with 21. There is one 2 and one 1 --> 1211
Start with 1211. There is one 1, one 2, and two 1s --> 111221

```
function lookSay(n){
  n = [n]
    const arr = Array.from(n.join(''))
    console.log(arr)
    const b = []  
    let j=1
    for(let i=0; i<arr.length; i++) {
        if(arr[i]===arr[i+1]) {
            j+=1
        } else {
            b.push(j)
            b.push(arr[i])
            j=1
        } 
    }
    return +b.join('')
  }
```
---
**Courses:**

* [HTML&CSS — первый шаг в IT](https://result.school/)

![сертификат](https://i.ibb.co/Q6CfW6j/start.png)

* [Марафон: 5 дней 5 проектов на JavaScript](https://result.school/products/marathon-js)

![сертификат](https://i.ibb.co/V0yDtFf/5.png)

---

**Languages:**

* English - [Intermediate](https://www.efset.org/cert/B4Gx8q)
* Russian - native