# Euheni Andreevich Yanson
32 years, 13.04.1989
![markdown-foto](img/euheni.png)

## Connection
* **+375298883889**
* **yanson.yauhen@gmail.com**
* **euhen (@jarvisssssssss)**
## About me
I appreciate a strong team and competent leadership. To work effectively, I need a friendly atmosphere and a clear understanding of the tasks assigned to me.
## Skills
* Hard: JavaScript, React, HTML, CSS, MySQL, Node.js, OOP, Gulp, Git, GitHub
* Soft: teaching, stress resistance, ability to learn
## Code examples
```
function timer(id, deadline) {
    function getTimeRemaining(endtime) {
        const t = Date.parse(endtime) - Date.parse(new Date()),
            days = Math.floor( (t/(1000*60*60*24)) ),
            seconds = Math.floor( (t/1000) % 60 ),
            minutes = Math.floor( (t/1000/60) % 60 ),
            hours = Math.floor( (t/(1000*60*60) % 24) );

        return {
            'total': t,
            'days': days,
            'hours': hours,
            'minutes': minutes,
            'seconds': seconds
        };
    }

    function getZero(num){
        if (num >= 0 && num < 10) { 
            return '0' + num;
        } else {
            return num;
        }
    }

    function setClock(selector, endtime) {

        const timer = document.querySelector(selector),
            days = timer.querySelector("#days"),
            hours = timer.querySelector('#hours'),
            minutes = timer.querySelector('#minutes'),
            seconds = timer.querySelector('#seconds'),
            timeInterval = setInterval(updateClock, 1000);

        updateClock();

        function updateClock() {
            const t = getTimeRemaining(endtime);

            days.innerHTML = getZero(t.days);
            hours.innerHTML = getZero(t.hours);
            minutes.innerHTML = getZero(t.minutes);
            seconds.innerHTML = getZero(t.seconds);

            if (t.total <= 0) {
                clearInterval(timeInterval);
            }
        }
    }

    setClock(id, deadline);
}

export default timer;
```
## Educational projects
* **resto**
    * HTML, CSS, JS, Webpack
    * https://github.com/jarvisssssssss/resto.git
* **got**
    * React, Redux, CSS, HTML
    * https://github.com/jarvisssssssss/got.git
* **Food**
    * JS, HTML, SCSS, PHP
    * https://github.com/jarvisssssssss/Food.git
* **Portfolio_Evgenij_Yanson**
    * HTML, JS, SCSS, BEM
    * https://github.com/jarvisssssssss/Portfolio_Evgenij_Yanson.git
## Education
1. 2018 - Vitebsk State University P.M. Masherova, Vitebsk
    * Master / Educational Management
2. Udemy
    * Udemy, Web developer
    * Udemy, JavaScript + React
## Languages
 * English
 * Russian
 * Belorussian