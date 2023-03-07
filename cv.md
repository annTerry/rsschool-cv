# Anna Kniazeva
![foto](foto_m.jpg)

## Contact information
* __Location:__ Saint-Petersburg, Russia
* __E-mail:__ alattery@gmail.com
* __Telegram:__ @annaKn
* __GitHub:__ [annTerry](https://github.com/annTerry)
* __LinkedIn:__ [Anna Kniazeva](https://www.linkedin.com/in/anna-kniazeva-23b732234/)

## About Me:
Web-developer since 2002 year. And all this time have been coding in vanilla JavaScript. I have been working  with Java, Perl, PHP etc. Have base knowledge in Node.JS. I like coding, looking for bugs causes, refactoring legacy projects and understanding foreign code. I can do both and FrontEnd, and BackEnd. But if I could choice, I prefer FrontEnd. I have more then 15 years of coding experience in different languages. But I changed my job only once, and it was many years ago. So I must say, most of my experience was with very little amount of project. All time I'm adding new features and fixing bugs in some old applications. And I really want something new. I'd want to be useful in improve quality and functionality of applications in modern company.

***
## Skills:
* HTML
* CSS, SCSS
* JavaScript, Typescript
* Node JS (Beginner)
* Java (Beginner +)
* Python, PHP, Perl, MySQL (have some experience)
* Webpack
* Git
* IntelliJ IDEA, VSCode
* Adobe Photoshop, Adobe Premiere
* React (in Progress)

## Code example:
```
export default function priceManager() {
    const priceObject = document.getElementById('priceList');
    const baseElements = Array.from(priceObject.getElementsByTagName('h5'));
    let activeElement = null;
    for (const headerElement of baseElements) {
        headerElement.addEventListener('click', () => {
            const liElement = headerElement.parentElement;
            const isActive = liElement.classList.contains('Active');
            if (activeElement) {
                activeElement.classList.remove('Active');
                activeElement = null;
            }
            if (!isActive) {
                liElement.classList.add('Active');
                activeElement = liElement;
            }
        })
    }
};
```