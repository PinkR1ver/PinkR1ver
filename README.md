<script src="https://cdnjs.cloudflare.com/ajax/libs/animejs/2.0.2/anime.min.js"></script>

<style>
    .ml6 {
      position: relative;
      font-weight: 900;
      font-size: 3.3em;
    }
    
    .ml6 .text-wrapper {
      position: relative;
      display: inline-block;
      padding-top: 0.2em;
      padding-right: 0.05em;
      padding-bottom: 0.1em;
      overflow: hidden;
    }
    
    .ml6 .letter {
      display: inline-block;
      line-height: 1em;
    }
    </style>

<script>
var textWrapper = document.querySelector('.ml6 .letters');
textWrapper.innerHTML = textWrapper.textContent.replace(/\S/g, "<span class='letter'>$&</span>");

anime.timeline({loop: true})
  .add({
    targets: '.ml6 .letter',
    translateY: ["1.1em", 0],
    translateZ: 0,
    duration: 750,
    delay: (el, i) => 50 * i
  }).add({
    targets: '.ml6',
    opacity: 0,
    duration: 1000,
    easing: "easeOutExpo",
    delay: 1000
  });
</script>
    
<h1 class="ml6">
  <span class="text-wrapper">
    <span class="letters">Hello, I'm Jude Wang</span>
  </span>
</h1>
## Hi, there 🤞🏻

Interested in everything about computer science (CS), with ambition to be full-stack engineer. Also, enjoy counter strike (CS)  👏

### Connect with me:

[<img align="left" alt="blog" width="22px" src="blogging.png" />][blog]
[<img align="left" alt="Twitter" width="22px" src="twitter.png" />][twitter]
[<img align="left" alt="Instagram" width="22px" src="instagram.png" />][instagram]
[<img align="left" alt="Mail" width="22px" src="gmail.png" />][mail] </br>


[blog]: https://pinkr1ver.com
[twitter]: https://twitter.com/pinkr1ver
[instagram]: https://instagram.com/pinkcred1t
[mail]: mailto:pinkr1veroops@gmail.com

### Here are the two cats named Maoqiu(Hairball) and Xiaohei(Little Black) 🐱‍💻
![Maoqiu&Xiaohei](https://i.ibb.co/rprRY7x/Maoqiu-Xiaohei.jpg)