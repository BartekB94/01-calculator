See the live version of [Calculator](https://bartekb94.github.io/01-calculator/)

###   Funkcjonalności programu 
- dodawanie (+)
- odejmowanie (-)
- mnożenie (*)
- dzielenie (/)
- potęgowanie (^)

---

### Fragmenty kodu

```
Calculator.prototype.power = function (num1, num2) {
        let result = 1;
        for (let i = 0; i < num2; i++) {
            result *= num1;
        }
        this.history.push(`${num1} * ${num2} = ${result}`);
}
```

```
function Calculator() {
    this.history = [];
    this.operations = {
        '+': this.add,
        '-': this.subtract,
        '*': this.multiply,
        '/': this.divide,
        '^': this.power
    }
}
```

---

## 🙋‍♂️ Feel free to contact me
Write sth nice ;) Find me on   <a href="https://www.linkedin.com/in/bartekb94/" target="_blank">
    <img align="center" src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank" />
  </a>

&nbsp;

## 👏 Thanks / Special thanks / Credits
Thanks to my [Mentor - devmentor.pl](https://devmentor.pl/) – for providing me with this task and for code review.

<!---
  


    
### materiały, które pomogły Ci uzyskać dany efekt
-
    
### reużywalne części projektu
-
  

&nbsp;



## *`Koniec sekcji notatek. Poniżej znajdziesz szablon właściwego README.`*
___




![screen or GIF of your app](https://via.placeholder.com/1000x300)


# Project Name

See the live version of [Project Name](https://bartekb94.github.io/01-js-basics/).

1-3 sentences about the project...

**Main features**:
- one
- two
- three


&nbsp;
 
## 💡 Technologies
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)


&nbsp;
 
## 🔗 See also

Are you interested in **techonologyName** and **technologyName**? See my other project [Interesting Project Name](https://devmentor.pl/podcast).

&nbsp;
 
## 💿 Installation

The project uses [node](https://nodejs.org/en/) and [npm](https://www.npmjs.com/). Having them installed, type into the terminal: `npm i`.


&nbsp;
 
## 🤔 Solutions provided in the project

- one

 &nbsp;

- two:
```
some example code

more code :)
```
 &nbsp;

- three

| Issue                     | Solution                       |     |
| ------------------------- | -----------------------------  | --- |
| one                       | `short code example`           |     |
| two                       | `short code example`           |     |
| thre                      | `short code example`           |     |

 &nbsp;
 
- four - some shortcut <kbd>Ctrl</kbd> + <kbd>C</kbd>

 &nbsp;
 
- five - example with a screenshot
<img alt='what it is' src="https://via.placeholder.com/500x200" />


&nbsp;

## 💭 Conclusions for future projects

I would like to improve...

#### This is the first issue:
```
and this is a code example
```

#### This is the second issue:
```
and this is a code example
```


&nbsp;

## 🙋‍♂️ Feel free to contact me
Write sth nice ;) Find me on <img align="center" src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank" />


&nbsp;

## 👏 Thanks / Special thanks / Credits
Thanks to my [Mentor - devmentor.pl](https://devmentor.pl/) – for providing me with this task and for code review.
-->
