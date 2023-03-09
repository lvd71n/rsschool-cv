# Vladislav Tyulin

![avatar](./IMG_1239.png)

### Junior Frontend developer

******

## Contact inforamtion

* E-mail: 1vd71n@protonmail.com
* Telegram: @Zontick
* GitHub: [14d71n](https://github.com/14d71n)
* LinkedIn: [vladislav-tyulin](https://www.linkedin.com/in/vladislav-tyulin-238308208/)

## About myself

After several years of working as engine engineer, warranty engineer and some part time activities I decided to switch my occupation. Thereby I started my way in web development. I'm attracted by its open community, availability of knowledge, creativity based approach towards work and possibility of doing the job remotly with ease.

## Skills

* HTML5
* CSS
* JavaScript (Fundamentals,Functional Programming, OOP, Asynchronous JavaScript), TypeScript.
* React, Express.js, Jest
* Version control: Git (remote service GitHub).
* CI/CD: CircleCI.
* MongoDB.
* Editors: VS Code.

## Code example:

"All Inclusive?" KATA from CODEWARS:
```
function containAllRots(strng, arr) {
    if(strng === "") {
        return true
    }

    let currentStrng = strng;
    const compArr = [currentStrng];
    for (let i = 0; i < currentStrng.length - 1; i++) {
        const newStrArr = [...currentStrng];
        const char = currentStrng[0];
        newStrArr.splice(0, 1);
        newStrArr.push(char);
        currentStrng = newStrArr.join('');
        compArr.push(currentStrng);
    }
    const result = compArr.every(elem => arr.includes(elem));
    return result;
}
```
## Education

* Kazan National Research Technical University named after A. N. Tupolev - KAI / Engeneer
  * Department for Jet Engines and Power Plants
* [MDN Web Docs](https://developer.mozilla.org/en-US/) - in progress
* [Education frontend project](https://github.com/Team-number-7/great-equalizer)
* [Education backend project](https://github.com/Team-number-7/great-equalizer-backend)

## Languages
* English - ![English result](eng_test.png)
* Russian - Native
* Ukrainian - Advanced