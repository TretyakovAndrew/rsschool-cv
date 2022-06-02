## Andrei Tretyakov
**Junior Frontend Developer**

---
### Contacts:
- **Location:** Belarus, Minsk
- **Phone number:** +375 29 660-56-04
- **Email:** drobservis@gmail.com
- **GitHub:** [TretyakovAndrew](https://github.com/TretyakovAndrew)

---
### About Myself
I want to learn Front-End development in RSSchool.

---
### Skills:
- HTML, CSS 
- JavaScript
- Version control: Git
- Windows, Linux (Ubuntu)
- Figma
- Python (basic knowledge)
- SQL (basic knowledge)
- Editors: VS Code, WebStorm, PyCharm
---
### Code Example:  

```
function whoseBicycle(diary1, diary2, diary3) {
    let commonArray = [Object.values(diary1), Object.values(diary2), Object.values(diary3)];
    let eachSonTotal = commonArray.map(total => total.reduce(
        (previousValue, currentValue) => previousValue + currentValue,
        0
    ));
    let bestIndex= eachSonTotal.lastIndexOf(Math.max(...eachSonTotal));

    return "I need to buy a bicycle for 
            my ${bestIndex===0?'first':bestIndex===1?'second':'third'} son."
}
```
---
### Courses:
- HTML, CSS on [htmlbook.ru](http://htmlbook.ru)
- JavaScript on [learnjavascript.ru](https://learn.javascript.ru/)
- Python, Beegeek School
---
### Languages:
- English (A2)
- Russian