# Resume

## Ilya Komar

 Contacts:
- Phone: +375296664475
- E-mail: helias@yandex.ru
- Skype: helias17

## My short-term goals
Improve JS level, learn react, find office job, because freelance has a lot of disadvantageы.

Skills
html, css/sass,  js, jquery, gulp, git, bem, mobile-first, wordpress

## Code example:
```
'use strict'

// Floating button for autoscroll to top of the page
// Button visible only after page scroll

{
  let scrollBtn = document.getElementsByClassName('scroll-btn')[0];
  let isVisible = false;
  let height = 2500;

  scrollBtn.addEventListener('click', ()=>{
    $('html, body').animate({ scrollTop: 0 }, '900');
  })

  document.addEventListener('scroll', ()=>{

    if ( window.scrollY > height && isVisible == false ) {
      scrollBtn.classList.remove('hidden');
      setTimeout(()=>{
        scrollBtn.classList.add('scroll-btn_visible');
      }, 100)
      isVisible = true;
    } else if ( window.scrollY < height && isVisible == true ) {
      scrollBtn.classList.remove('scroll-btn_visible');
      setTimeout(()=>{
        scrollBtn.classList.add('hidden');
      }, 100)
      isVisible = false;
    }

  })
}
```

## Experience 
Now I'm working as a freelancer. Make responsitive crossbrowser webpages from PSD.
Example: [LiveSklad - CRM for small biz](https://helias17.github.io/livesklad/)

## Education
- National Technical University (Minsk)
- English courses in Central House of Officers (2 years)
- Interactive online courses HTML ACADEMY "Professional HTML & CSS, level 2" - [Certificate](https://assets.htmlacademy.ru/certificates/intensive/63/236662.pdf)
- Self education (youtube, articles, manuals)


## English knowledges
I've started to study english in 5 class of a grade school. From 9 to 10 class I also was learning language at courses in Central House of Officers (2 years, 3 times a week for 2 hours). Now I try to expand my vocabulary, learn new words and phrases, read english articles and watch movies.
