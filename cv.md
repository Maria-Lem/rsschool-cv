## Mariia Alemaskina

### Contacts

* +7 (911) 092-81-06
* maria131621@yandex.ru
* [Telegram](https://t.me/Maria131621)
* [GitHub](https://github.com/Maria-Lem)
* [Vk](https://vk.com/maria_lem131621)

### Summary

> I aspire to become a Full Stack developer. I am an energetic, communicative and self-motivated person who is always eager to absorb as much knowledge and insight as possible in the pursuance of my goals. With my previous work experience in accountancy I have developed a responsible approach to any task that I undertake and good problem-solving skills.

### Skills

* __Languages:__ HTML, CSS, Javascript (basics), PHP (basics);
* __Web libs:__ Bootstrap, jQuery;
* __Web Dev tools:__ Gulp, npm;
* __Source control:__ Git, GitHub;
* __Graphic editors:__ Figma, Photoshop;
* Responsive design, BEM, Sass;

### Code Example

```
import {radioPlayerInit} from './radioPlayer.js';
import {musicPlayerInit} from './musicPlayer.js';
import {videoPlayerInit} from './videoPlayer.js';

const playerBtn = document.querySelectorAll('.player-btn'),
  playerBlock = document.querySelectorAll('.player-block'),
  temp = document.querySelector('.temp');

const deactivationPlayer = () => {
  temp.style.display = 'none';
  playerBtn.forEach(item => item.classList.remove('active'));
  playerBlock.forEach(item => item.classList.remove('active'));
}

playerBtn.forEach((btn, i) => btn.addEventListener('click', () => {
  deactivationPlayer();
  btn.classList.add('active');
  playerBlock[i].classList.add('active');
}));

radioPlayerInit();
musicPlayerInit();
videoPlayerInit();
```

### Experience

I have worked on several study projects, such as:

* [Repair design](https://maria-lem.github.io/repair-design/)
* [YTunes](https://maria-lem.github.io/YTunes/)
* [Fylo landing page](https://fylo-landing-page-iota-two.vercel.app/)
* [The Witcher landing page](https://maria-lem.github.io/the-Witcher-landing-page/)
* [Delivery Food](https://maria-lem.github.io/delivery-food/)

### Education

* __Bachelor of Economics: Accountancy and audit.__ Saint Petersburg State University of Economics - Saint-Petersburg, Russia;
* Course by Glo Academy "Web-Start";
* Online courses on [Code Basics](https://ru.code-basics.com/) (HTML, CSS, JavaScript);
* Harvard University's online course CS50;

### English

Upper intermediate (B2)