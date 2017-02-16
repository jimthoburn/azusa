---
title: Azusa High School, Every student college and career ready
classname: home
layout: default
has_wide_content: true
image: "/images/photos/three-students.png"
image_focus: bottom
---

<style>
/*
body > main::before {
  content: "";
  background-color: white;
  height: 1.5em;
  width: 120%;
  margin-top: -2.25em;
  position: absolute;
  z-index: 3;
  left: -10%;
  transform: rotate(-2deg);
}
  @media (min-width: 60em) {
    body > main::before {
      margin-top: -4.5em;
      height: 3em;
    }
  }

*/
body {
  background-color: rgb(244, 209, 81); /* --gold */
  background-color: rgb(237, 237, 239);
}
body > main::before,
body > main {
  background-color: rgb(244, 209, 81); /* --gold */
  background-color: rgb(237, 237, 239);
}
/*
body > .image {
  background-color: rgb(237, 237, 239);
  background-image: url(/images/athletics.jpg);
  background-position: center;
  background-size: cover;
}
*/
body > .image {
  background-color: rgb(46, 127, 182); /* --ocean */
  background-color: white;
  background-color: rgb(244, 209, 81); /* --gold */
  background-color: rgb(237, 237, 239);
  /*
  transform: skew(0, -2deg) translate(0, -5vh);
  */
  height: 10em;
  min-height: 80vmax;
}
/*
body > .image img {
  transform: skew(0, 2deg) translate(0, 5vh);
}
*/
body > .image::before,
body > .image::after {
  display: none;
}
body > .image img {
  height: auto;
  width: 100%;
  position: absolute;
  top: 50vh;
  right: 0;
  z-index: 9999;
}

body.image-reverse > .image img {
  left: 0.75em;
}
@media (min-width: 60em) {
  body.image-reverse > .image img {
  lefteft: 3em;
  }
}


body > main::before {
  display: none;
}
body > main > div:first-of-type {
  background: white;
  position: relative;
  z-index: 9999999999;
  padding: 3em 1.5em;
  margin: 0 -1.5em -3em;
  background: rgb(57, 164, 208); /* --light-blue */
  color: white;
  background-image: url(/images/aztec-pattern.svg);
  background-position: top;
  background-size: auto 1.5em;
  background-repeat: repeat-x;
  /*
  background-image: url(/images/aztec-circle.png);
  background-position: top;
  background-size: 100% 100%;
  */
  /*
  box-sizing: border-box;
  display: flex;
  align-content: center;
  align-items: center;
  justify-content: center;
  padding-left: 6em !important;
  padding-right: 6em !important;
  border-radius: 50%;
  height: 100vw;
  -webkit-clip-path: circle(50vw at 50% 50%);
  transform: skew(0, 2deg) translate(0, 5%);
  transform: perspective(600px) rotateY(5deg);
  */

  /*Chrome,Safari*/
  /*
  -webkit-clip-path: polygon(0 0,6.25% 5%,25% 0,62.5% 5%,75% 0,87.5% 5%,100% 0,100% 100%,92.5% 95%,75% 100%,50% 95%,25% 100%,12.5% 95%,0 100%);
  margin-top: -3em;
  padding-top: 3em !important;
  padding-bottom: 3em !important;
  transform: translate(0, 5%);
  */
}
@media (min-width: 60em) {
  body > main > div:first-of-type {
    padding-top: 4.5em !important;
    padding-bottom: 4.5em !important;
  }
}
body > main > div:first-of-type > * {
}
body > main > div:first-of-type p a {
  color: inherit;
}
body > main > div:first-of-type p {
    text-align: center;
    margin-left: auto;
    margin-right: auto;
}
@media (min-width: 60em) {
  body > main > div:first-of-type {
    padding: 3em;
    margin-left: -3em;
    margin-right: -3em;
    margin-bottom: -3em;
  }
  body > main > div:first-of-type p {
    font-size: 2vmax;
  }
}
body > main > div:first-of-type h2:first-child {
  margin-top: 0.75rem;
}
body.image-reverse main h1 {
  left: auto;
  right: 1.5rem;
  max-width: none;
  text-align: right;
}
/*
@media (min-aspect-ratio: 1/1) {
  body > .image {
    height: 65vh;
    min-height: 65vh;
  }
  body > .image img {
    top: 30vh;
  }
  body > .image img {
    width: 40vw;
    height: auto;
    right: -3em;
  }
  body > main > div:first-of-type {
    background: transparent;
    position: static;
    padding: 0;
    margin: 0;
    margin-right: 35%;
  }
  body.image-reverse main h1 {
    margin-left: 0;
    left: 50vw;
    right: auto;
    margin-right: 3rem;
    text-align: left;
  }
  body.image-reverse > main > div:first-of-type {
    margin-right: 0;
    margin-left: 50vw;
    margin-left: calc(50vw - 1.5em);
  }
  @media (min-width: 60em) {
    body.image-reverse > main > div:first-of-type {
      margin-left: calc(50vw - 3em);
    }
  }
}
*/
/*
@media (min-width: 35em) {
  body.image-reverse main h1 {
    margin-left: 0;
    left: 50vw;
    right: auto;
    margin-right: 3rem;
    text-align: left;
  }
  body.image-reverse main > div:first-of-type p,
  body.image-reverse main > div:first-of-type ul {
    max-width: none;
    margin-left: 50vw;
    margin-left: calc(50vw - 3em);
    margin-right: 0;
  }
}
*/

/*
body > header h2,
body > header h2 + p {
  color: black;
  text-shadow: none;
}
body > header > a {
  margin-top: 1em;
}
*/
body > header > a {
  margin-top: -3.75em;
  display: table;
  margin-left: auto;
  margin-right: auto;
  padding-left: 0;
  padding-right: 0;
}
body > header h2 img {
  display: block;
  position: static;
  margin-left: auto;
  margin-right: auto;
  transform: none;
  margin-bottom: 0.75em;
}
body > header h2,
body > header h2 + p {
  color: rgb(244, 209, 81); /* --gold */
  color: white;
  color: rgb(46, 127, 182); /* --ocean */
  text-shadow: none;
  color: rgb(57, 164, 208); /* --light-blue */
  color: rgb(40, 41, 43); /* --tungsten */
  text-shadow: none;
  text-align: center;
}
/*
body > header h2 img {
  transform: translateY(-65%);
}
body > main > p {
  margin-right: 50vw;
}
*/
main h1 {
  position: absolute;
  z-index: 3;
  text-align: center;
  /*
  transform: translate(0, -100%);
  margin-top: -1.5rem;
  */
  top: 11.25rem;
  margin-right: 1.5rem;
  color: rgb(244, 209, 81); /* --gold */
  color: white;
  color: rgb(46, 127, 182); /* --ocean */
  color: rgb(57, 164, 208); /* --light-blue */
}
@media (min-width: 30em) {
  main h1 {
    margin-right: 3rem;
    font-size: 6vmax;
    padding-left: 5vw;
    padding-right: 5vw;
  }
}
main h1 + h2,
main h1 + p {
  margin-top: 0;
}
figure {
  margin-top: 1.5em;
  margin-left: -4.5em;
  margin-right: -4.5em;
  margin-bottom: -4.5em;
  max-width: none;
  position: relative;
  z-index: 99999;
  transform: rotate(-2deg);
  overflow: hidden;
  background: rgb(51, 51, 51);
}
@media (min-width: 60em) {
  figure {
    margin-bottom: -7.5em;
  }
}
figure img {
  width: 100%;
  height: auto;
  max-width: none;
  transform: rotate(2deg) scale(1.125);
}
/*
figure {
  transform: rotate(-5deg) scale(0.85) translate(-6em, 0);
  margin-top: 1.5em;
  margin-bottom: 3em;
}
figure img {
  transform: rotate(5deg) scale(1.15);
}
*/
.staff-list {
  margin-top: 3em;
  padding: 1px 1.5em 3em 1.5em;
  margin-left: -1.5em;
  margin-right: -1.5em;
  background-color: white;
  position: relative;
  z-index: 99999;
}
@media (min-width: 60em) {
  .staff-list {
    padding-left: 3em;
    padding-right: 3em;
    margin-left: -3em;
    margin-right: -3em;
  }
}
.summaries {
  margin-top: 0;
  background-color: white;
  position: relative;
  z-index: 99999;
}
</style>

<style media="false">
body.has-image > header {
  color: inherit;
  text-shadow: none;
}
.nav-link {
  z-index: 99999999999999 !important;
}
body > .image {
  background: transparent;
  background-color: rgb(237, 237, 239);
  padding-top: 30em;
}
body > .image img {
  width: 100%;
  height: auto;
}
main > div:first-of-type {
  position: absolute;
  z-index: 9999;
  top: 12em;
  margin-right: 1.5em;
}

@media (min-aspect-ratio: 1/1) {
  body > .image {
    padding-top: 15em;
  }
  main > div:first-of-type {
    top: 10.5em;
  }
}

/*
body > .image img {
  position: relative;
  z-index: 2;
}
*/
.staff-list {
  background-color: white;
}
.staff-list h2 {
  margin-top: 0;
}
main > div:first-of-type + p {
  margin-top: 0;
}

    .image::before,
    .image::after {
      display: none;
    }
@supports (object-fit: cover) {
  .image {
    padding-top: 20vh;
    position: static;
  }
  .image img {
    width: 100%;
    height: 85vh;
    position: relative;
    z-index: 9999;
  }
  @media (min-aspect-ratio: 1/1) {
    .image {
      padding-top: 0;
    }
    .image img {
      height: 100vh;
      object-position: top !important;
    }
  }
}

/*
.summaries .parents-summary {
  transform: rotate(2deg);
  padding-bottom: 3em;
  margin-bottom: -3em;
}
.summaries .parents-summary > * {
  transform: rotate(-2deg);
}
.summaries .calendar-summary {
  transform: rotate(-2deg);
}
.summaries .calendar-summary > * {
  transform: rotate(2deg);
}
*/
</style>

<!--
Once an Aztec<br />
Always an Aztec!
-->

<h1>Every Student College <span class="lowercase">and</span> <span class="avoid-break">Career Ready</span></h1>

<div markdown="1">

  <div>
    <p>Our mission is to provide a 21st century education that emphasizes critical thinking, effective communication, and respect for diversity and creativity in a safe and positive environment.</p>

    <p>Learn more <a href="/about">about our school</a></p>
  </div>

</div>

<!--
<div class="introduction">
  <img src="/images/students/IMG_0760.jpg" width="500" alt="" />
  <div>
    <h1>Bringing aspiration into reality</h1>

    <p>Sierra High School is a place where students have a second opportunity to achieve academic success. To bring this aspiration into reality we:</p>

    <ul>
      <li>model and build good relationships</li>
      <li>develop skills and knowledge</li>
      <li>foster independent thinking in a safe environment</li>
    </ul>
    <p>Learn more <a href="about.html">about our school</a></p>
  </div>
</div>
<script>
(function() {
  var images = [
    '/images/students/IMG_0284.jpg',
    '/images/students/IMG_0325.jpg',
    '/images/students/IMG_0381.jpg',
    '/images/students/IMG_0482.jpg',
    '/images/students/IMG_0614.jpg',
    '/images/students/IMG_0683.jpg',
    '/images/students/IMG_0731.jpg',
    '/images/students/IMG_0760.jpg',
    '/images/students/IMG_1065.jpg'
  ];
  var min = 0;
  var max = images.length - 1;
  var random = Math.floor(Math.random() * (max - min + 1) + min);
  var image = document.querySelector('.introduction img');
  image.src = images[random];
  if (images[random].indexOf('IMG_0284.jpg') >= 0 ||
      images[random].indexOf('IMG_0381.jpg') >= 0 ||
      images[random].indexOf('IMG_0482.jpg') >= 0 ||
      images[random].indexOf('IMG_0614.jpg') >= 0 ||
      images[random].indexOf('IMG_1065.jpg') >= 0) {
    image.parentNode.className += ' reverse';
  }
})();
</script>
-->

<div class="staff-list">
  <h2>Our Teachers</h2>
  <ul>
    <li>
      <a href="/staff">
        <img src="/images/teachers/img_2203.jpg" width="200" alt="TODO: Add Teacher’s Name" />
        <h3>Mrs. Beaton</h3>
        <p class="title">English, Yearbook &amp; Leadership</p>
      </a>
    </li>
    <li>
      <a href="/staff">
        <img src="/images/teachers/img_1941.jpg" width="200" alt="TODO: Add Teacher’s Name" />
        <h3>Ms. Benavides</h3>
        <p class="title">English</p>
      </a>
    </li>
    <li>
      <a href="/staff">
        <img src="/images/teachers/img_2140.jpg" width="200" alt="TODO: Add Teacher’s Name" />
        <h3>Mrs. Bushem</h3>
        <p class="title">Math</p>
      </a>
    </li>
    <li>
      <a href="/staff">
        <img src="/images/teachers/img_1892.jpg" width="200" alt="TODO: Add Teacher’s Name" />
        <h3>Mr. Calvillo</h3>
        <p class="title">Music</p>
      </a>
    </li>
  </ul>
  <p>See more <a href="/staff">staff members</a></p>
</div>


<div class="summaries">
  <div class="facilities-summary text" markdown="1">
## Facilities

*   Gym
*   Theater
*   4 computer labs
*   Track and field
*   Ceramics lab
*   Engineering lab
*   Band room
*   Choir room
  </div>

  <div class="calendar-summary text" markdown="1">
## Calendar

January 9
: Planning Day<br />_No School_

January 10
: Teacher PLC Day<br />_No School_

January 11
: Students Return from Break

[See full calendar](http://info.azusahighschool.jimthoburn.com/cms/month-d=x&group_id=1301752510104)
  </div>

  <div class="parents-summary text" markdown="1">
## Parents & students

Learn about attendance, handbooks, dress code and more on the [parents & students](/parents/) page.
  </div>
</div>

<section class="announcements">

<header>
<h2>News &amp; Announcements</h2>
</header>

<ul>
<li markdown="1">

### Winter break is from December 23, 2016 - January 10, 2017.

Students return to school on January 11th.

</li>
<li markdown="1">

### Math tutoring is now available

Monday through Thursday from 3:00 - 4:00 p.m. in the Library. Take advantage of this opportunity!

</li>
<!--
<li markdown="1">

### Congratulations, Brad Kear — 2015–2016 Teacher of the Year!

<img alt="" src="http://ahs-ausd-ca.schoolloop.com/uimg/image/1301752510104/1331967107019/1413182913155.jpg?1462815786781" />

</li>
<li markdown="1">

### Summer Chandler - 2016 Classified Employee of the Year

<img alt="" src="http://ahs-ausd-ca.schoolloop.com/uimg/file/1471331230544/6029079328627407908.jpg?1480630558846" />

</li>
<li markdown="1">

### 2017 Seniors

Call J. Garcia Photo Studio for senior portrait appointments

**626-969-8488**

</li>
-->

</ul>
</section>

<div class="feature">
  <h2>
    <svg class="icon" viewBox="0 0 24 24" width="48" height="48">
      <switch>
        <path fill="white" d="M22,19.4c0,1.4-1.2,2.6-2.6,2.6H4.6C3.2,22,2,20.8,2,19.4V4.6C2,3.2,3.2,2,4.6,2h14.9C20.8,2,22,3.2,22,4.6 V19.4z M19.7,10.5H18c0.2,0.5,0.3,1.1,0.3,1.7c0,3.3-2.8,6-6.2,6c-3.4,0-6.2-2.7-6.2-6c0-0.6,0.1-1.2,0.3-1.7H4.2v8.4 c0,0.4,0.4,0.8,0.8,0.8h13.9c0.4,0,0.8-0.4,0.8-0.8V10.5z M12,8.1c-2.2,0-4,1.7-4,3.9c0,2.1,1.8,3.9,4,3.9c2.2,0,4-1.7,4-3.9 C16,9.8,14.2,8.1,12,8.1z M19.7,5.1c0-0.5-0.4-0.9-0.9-0.9h-2.3c-0.5,0-0.9,0.4-0.9,0.9v2.1c0,0.5,0.4,0.9,0.9,0.9h2.3 c0.5,0,0.9-0.4,0.9-0.9L19.7,5.1L19.7,5.1z"></path>
        <foreignObject>Instagram</foreignObject>
      </switch>
    </svg>
    @azusahighschool
  </h2>
  <!--
  <p class="more">See more <a href="/news">news &amp; announcements</a></p>
  -->

  <a href="https://www.instagram.com">
    <img src="/images/photos/band.jpg" alt="" />
    <p>Congratulations to the Azusa High Band &amp; Pageantry Corps for another First Place Gold Medal Finish at the <abbr title="Southern California School Band and Orchestra Association">SCSBOA</abbr> Championships!  They also received the High Auxiliary Award &amp; High Caption Award for Music Performance, Visual Performance &amp; Effect.  Great job Aztecs!</p>
  </a>

  <a href="https://www.instagram.com" class="icon">
    <svg class="comment icon" viewBox="0 0 24 24" width="24" height="24">
      <path fill="white" d="M2.2,8.9c0,1,0.3,1.9,1,2.8c0.7,0.9,1.6,1.5,2.8,2c1.2,0.5,2.5,0.7,3.9,0.7c0.4,0,0.8,0,1.3-0.1c1.1,1,2.5,1.7,4,2.1
        c0.3,0.1,0.6,0.1,1,0.2c0.1,0,0.2,0,0.3-0.1c0.1-0.1,0.1-0.1,0.2-0.3v0c0,0,0-0.1,0-0.1c0,0,0-0.1,0-0.1c0,0,0,0,0-0.1L16.5,16
        c0,0,0,0-0.1-0.1c0,0-0.1-0.1-0.1-0.1c0,0-0.1-0.1-0.3-0.3c-0.1-0.2-0.2-0.3-0.3-0.3s-0.2-0.2-0.3-0.3c-0.1-0.2-0.2-0.3-0.3-0.4
        c-0.1-0.1-0.1-0.3-0.2-0.5s-0.2-0.4-0.2-0.7c0.9-0.5,1.6-1.2,2.1-1.9s0.8-1.6,0.8-2.4c0-0.8-0.2-1.5-0.6-2.2s-1-1.3-1.7-1.8
        S14,4.1,13,3.8s-2-0.4-3-0.4c-1.4,0-2.7,0.2-3.9,0.7S4,5.2,3.3,6.1S2.2,7.9,2.2,8.9z"></path>
    </svg>
    2
  </a>

  <a href="https://www.instagram.com" class="icon">
    <svg class="heart icon" viewBox="0 0 24 24" width="24" height="24">
      <path fill="white" d="M17.631 5.93c-0.394-0.913-1.185-1.682-2.281-2.158-0.968-0.422-2.012-0.471-2.96-0.214s-1.801 0.956-2.388 1.767c-0.588-0.811-1.44-1.511-2.389-1.767-0.949-0.258-1.991-0.207-2.96 0.214-1.096 0.476-1.885 1.243-2.281 2.158-0.394 0.912-0.397 1.974 0.103 3.027 1.062 2.257 7.494 7.55 7.529 7.64 0.033-0.090 6.466-5.383 7.53-7.64 0.498-1.053 0.496-2.115 0.101-3.027z"></path>
    </svg>
    115
  </a>
</div>

<ul class="news-summary">
  <li>
    <a href="https://www.instagram.com">
      <img src="http://ahs-ausd-ca.schoolloop.com/uimg/file/1471331230544/4318864776100264058.jpg" alt="" />
      <span>Band &amp; Pageantry</span>
    </a>

    <a href="https://www.instagram.com" class="icon">
      <svg class="comment icon" viewBox="0 0 24 24" width="24" height="24">
        <path fill="white" d="M2.2,8.9c0,1,0.3,1.9,1,2.8c0.7,0.9,1.6,1.5,2.8,2c1.2,0.5,2.5,0.7,3.9,0.7c0.4,0,0.8,0,1.3-0.1c1.1,1,2.5,1.7,4,2.1
          c0.3,0.1,0.6,0.1,1,0.2c0.1,0,0.2,0,0.3-0.1c0.1-0.1,0.1-0.1,0.2-0.3v0c0,0,0-0.1,0-0.1c0,0,0-0.1,0-0.1c0,0,0,0,0-0.1L16.5,16
          c0,0,0,0-0.1-0.1c0,0-0.1-0.1-0.1-0.1c0,0-0.1-0.1-0.3-0.3c-0.1-0.2-0.2-0.3-0.3-0.3s-0.2-0.2-0.3-0.3c-0.1-0.2-0.2-0.3-0.3-0.4
          c-0.1-0.1-0.1-0.3-0.2-0.5s-0.2-0.4-0.2-0.7c0.9-0.5,1.6-1.2,2.1-1.9s0.8-1.6,0.8-2.4c0-0.8-0.2-1.5-0.6-2.2s-1-1.3-1.7-1.8
          S14,4.1,13,3.8s-2-0.4-3-0.4c-1.4,0-2.7,0.2-3.9,0.7S4,5.2,3.3,6.1S2.2,7.9,2.2,8.9z"></path>
      </svg>
      2
    </a>

    <a href="https://www.instagram.com" class="icon">
      <svg class="heart icon" viewBox="0 0 24 24" width="24" height="24">
        <path fill="white" d="M17.631 5.93c-0.394-0.913-1.185-1.682-2.281-2.158-0.968-0.422-2.012-0.471-2.96-0.214s-1.801 0.956-2.388 1.767c-0.588-0.811-1.44-1.511-2.389-1.767-0.949-0.258-1.991-0.207-2.96 0.214-1.096 0.476-1.885 1.243-2.281 2.158-0.394 0.912-0.397 1.974 0.103 3.027 1.062 2.257 7.494 7.55 7.529 7.64 0.033-0.090 6.466-5.383 7.53-7.64 0.498-1.053 0.496-2.115 0.101-3.027z"></path>
      </svg>
      115
    </a>
  </li>
  <li>
    <a href="https://www.instagram.com">
      <img src="http://ahs-ausd-ca.schoolloop.com/uimg/file/1471331230544/3141578244695411231.jpg" />
      <span>Band &amp; Pageantry</span>
    </a>

    <a href="https://www.instagram.com" class="icon">
      <svg class="comment icon" viewBox="0 0 24 24" width="24" height="24">
        <path fill="white" d="M2.2,8.9c0,1,0.3,1.9,1,2.8c0.7,0.9,1.6,1.5,2.8,2c1.2,0.5,2.5,0.7,3.9,0.7c0.4,0,0.8,0,1.3-0.1c1.1,1,2.5,1.7,4,2.1
          c0.3,0.1,0.6,0.1,1,0.2c0.1,0,0.2,0,0.3-0.1c0.1-0.1,0.1-0.1,0.2-0.3v0c0,0,0-0.1,0-0.1c0,0,0-0.1,0-0.1c0,0,0,0,0-0.1L16.5,16
          c0,0,0,0-0.1-0.1c0,0-0.1-0.1-0.1-0.1c0,0-0.1-0.1-0.3-0.3c-0.1-0.2-0.2-0.3-0.3-0.3s-0.2-0.2-0.3-0.3c-0.1-0.2-0.2-0.3-0.3-0.4
          c-0.1-0.1-0.1-0.3-0.2-0.5s-0.2-0.4-0.2-0.7c0.9-0.5,1.6-1.2,2.1-1.9s0.8-1.6,0.8-2.4c0-0.8-0.2-1.5-0.6-2.2s-1-1.3-1.7-1.8
          S14,4.1,13,3.8s-2-0.4-3-0.4c-1.4,0-2.7,0.2-3.9,0.7S4,5.2,3.3,6.1S2.2,7.9,2.2,8.9z"></path>
      </svg>
      2
    </a>

    <a href="https://www.instagram.com" class="icon">
      <svg class="heart icon" viewBox="0 0 24 24" width="24" height="24">
        <path fill="white" d="M17.631 5.93c-0.394-0.913-1.185-1.682-2.281-2.158-0.968-0.422-2.012-0.471-2.96-0.214s-1.801 0.956-2.388 1.767c-0.588-0.811-1.44-1.511-2.389-1.767-0.949-0.258-1.991-0.207-2.96 0.214-1.096 0.476-1.885 1.243-2.281 2.158-0.394 0.912-0.397 1.974 0.103 3.027 1.062 2.257 7.494 7.55 7.529 7.64 0.033-0.090 6.466-5.383 7.53-7.64 0.498-1.053 0.496-2.115 0.101-3.027z"></path>
      </svg>
      115
    </a>
  </li>
  <li>
    <a href="https://www.instagram.com">
      <img src="http://ahs-ausd-ca.schoolloop.com/uimg/image/1330874821019/1331967107018/1346922968544.jpg" />
      <span>Band &amp; Pageantry</span>
    </a>

    <a href="https://www.instagram.com" class="icon">
      <svg class="comment icon" viewBox="0 0 24 24" width="24" height="24">
        <path fill="white" d="M2.2,8.9c0,1,0.3,1.9,1,2.8c0.7,0.9,1.6,1.5,2.8,2c1.2,0.5,2.5,0.7,3.9,0.7c0.4,0,0.8,0,1.3-0.1c1.1,1,2.5,1.7,4,2.1
          c0.3,0.1,0.6,0.1,1,0.2c0.1,0,0.2,0,0.3-0.1c0.1-0.1,0.1-0.1,0.2-0.3v0c0,0,0-0.1,0-0.1c0,0,0-0.1,0-0.1c0,0,0,0,0-0.1L16.5,16
          c0,0,0,0-0.1-0.1c0,0-0.1-0.1-0.1-0.1c0,0-0.1-0.1-0.3-0.3c-0.1-0.2-0.2-0.3-0.3-0.3s-0.2-0.2-0.3-0.3c-0.1-0.2-0.2-0.3-0.3-0.4
          c-0.1-0.1-0.1-0.3-0.2-0.5s-0.2-0.4-0.2-0.7c0.9-0.5,1.6-1.2,2.1-1.9s0.8-1.6,0.8-2.4c0-0.8-0.2-1.5-0.6-2.2s-1-1.3-1.7-1.8
          S14,4.1,13,3.8s-2-0.4-3-0.4c-1.4,0-2.7,0.2-3.9,0.7S4,5.2,3.3,6.1S2.2,7.9,2.2,8.9z"></path>
      </svg>
      2
    </a>

    <a href="https://www.instagram.com" class="icon">
      <svg class="heart icon" viewBox="0 0 24 24" width="24" height="24">
        <path fill="white" d="M17.631 5.93c-0.394-0.913-1.185-1.682-2.281-2.158-0.968-0.422-2.012-0.471-2.96-0.214s-1.801 0.956-2.388 1.767c-0.588-0.811-1.44-1.511-2.389-1.767-0.949-0.258-1.991-0.207-2.96 0.214-1.096 0.476-1.885 1.243-2.281 2.158-0.394 0.912-0.397 1.974 0.103 3.027 1.062 2.257 7.494 7.55 7.529 7.64 0.033-0.090 6.466-5.383 7.53-7.64 0.498-1.053 0.496-2.115 0.101-3.027z"></path>
      </svg>
      115
    </a>
  </li>
</ul>


<div class="feature">
  <!--
  <h2>
    <svg class="icon" viewBox="0 0 24 24" width="48" height="48">
      <switch>
        <path fill="white" d="M22,19.4c0,1.4-1.2,2.6-2.6,2.6H4.6C3.2,22,2,20.8,2,19.4V4.6C2,3.2,3.2,2,4.6,2h14.9C20.8,2,22,3.2,22,4.6 V19.4z M19.7,10.5H18c0.2,0.5,0.3,1.1,0.3,1.7c0,3.3-2.8,6-6.2,6c-3.4,0-6.2-2.7-6.2-6c0-0.6,0.1-1.2,0.3-1.7H4.2v8.4 c0,0.4,0.4,0.8,0.8,0.8h13.9c0.4,0,0.8-0.4,0.8-0.8V10.5z M12,8.1c-2.2,0-4,1.7-4,3.9c0,2.1,1.8,3.9,4,3.9c2.2,0,4-1.7,4-3.9 C16,9.8,14.2,8.1,12,8.1z M19.7,5.1c0-0.5-0.4-0.9-0.9-0.9h-2.3c-0.5,0-0.9,0.4-0.9,0.9v2.1c0,0.5,0.4,0.9,0.9,0.9h2.3 c0.5,0,0.9-0.4,0.9-0.9L19.7,5.1L19.7,5.1z"></path>
        <foreignObject>Instagram</foreignObject>
      </switch>
    </svg>
    @azusahighschool
  </h2>
  -->
  <!--
  <p class="more">See more <a href="/news">news &amp; announcements</a></p>
  -->

  <a href="https://www.instagram.com">
    <img src="/images/photos/aHR0cDovL2Focy1hdXNkLWNhLnNjaG9vbGxvb3AuY29tL3VpbWcvaW1hZ2UvMTMzMDg3NDgyMTAxOS8xNDcxMzMxMjMwNTQ0LzE0NzM5MjQ3Mzc4NTQuanBnP2Nyb3BUb3A9MzcmY3JvcFJpZ2h0PTk1MCZjcm9wQm90dG9tPTcxMiZjcm9wTGVmdD01MCZiYXNpc1dpZHRoPTEwMDA=.jpeg" alt="" />
    <p>The Aztec Store is now open!</p>
  </a>

  <a href="https://www.instagram.com" class="icon">
    <svg class="comment icon" viewBox="0 0 24 24" width="24" height="24">
      <path fill="white" d="M2.2,8.9c0,1,0.3,1.9,1,2.8c0.7,0.9,1.6,1.5,2.8,2c1.2,0.5,2.5,0.7,3.9,0.7c0.4,0,0.8,0,1.3-0.1c1.1,1,2.5,1.7,4,2.1
        c0.3,0.1,0.6,0.1,1,0.2c0.1,0,0.2,0,0.3-0.1c0.1-0.1,0.1-0.1,0.2-0.3v0c0,0,0-0.1,0-0.1c0,0,0-0.1,0-0.1c0,0,0,0,0-0.1L16.5,16
        c0,0,0,0-0.1-0.1c0,0-0.1-0.1-0.1-0.1c0,0-0.1-0.1-0.3-0.3c-0.1-0.2-0.2-0.3-0.3-0.3s-0.2-0.2-0.3-0.3c-0.1-0.2-0.2-0.3-0.3-0.4
        c-0.1-0.1-0.1-0.3-0.2-0.5s-0.2-0.4-0.2-0.7c0.9-0.5,1.6-1.2,2.1-1.9s0.8-1.6,0.8-2.4c0-0.8-0.2-1.5-0.6-2.2s-1-1.3-1.7-1.8
        S14,4.1,13,3.8s-2-0.4-3-0.4c-1.4,0-2.7,0.2-3.9,0.7S4,5.2,3.3,6.1S2.2,7.9,2.2,8.9z"></path>
    </svg>
    2
  </a>

  <a href="https://www.instagram.com" class="icon">
    <svg class="heart icon" viewBox="0 0 24 24" width="24" height="24">
      <path fill="white" d="M17.631 5.93c-0.394-0.913-1.185-1.682-2.281-2.158-0.968-0.422-2.012-0.471-2.96-0.214s-1.801 0.956-2.388 1.767c-0.588-0.811-1.44-1.511-2.389-1.767-0.949-0.258-1.991-0.207-2.96 0.214-1.096 0.476-1.885 1.243-2.281 2.158-0.394 0.912-0.397 1.974 0.103 3.027 1.062 2.257 7.494 7.55 7.529 7.64 0.033-0.090 6.466-5.383 7.53-7.64 0.498-1.053 0.496-2.115 0.101-3.027z"></path>
    </svg>
    115
  </a>
</div>

<div class="feature">
  <!--
  <h2>
    <svg class="icon" viewBox="0 0 24 24" width="48" height="48">
      <switch>
        <path fill="white" d="M22,19.4c0,1.4-1.2,2.6-2.6,2.6H4.6C3.2,22,2,20.8,2,19.4V4.6C2,3.2,3.2,2,4.6,2h14.9C20.8,2,22,3.2,22,4.6 V19.4z M19.7,10.5H18c0.2,0.5,0.3,1.1,0.3,1.7c0,3.3-2.8,6-6.2,6c-3.4,0-6.2-2.7-6.2-6c0-0.6,0.1-1.2,0.3-1.7H4.2v8.4 c0,0.4,0.4,0.8,0.8,0.8h13.9c0.4,0,0.8-0.4,0.8-0.8V10.5z M12,8.1c-2.2,0-4,1.7-4,3.9c0,2.1,1.8,3.9,4,3.9c2.2,0,4-1.7,4-3.9 C16,9.8,14.2,8.1,12,8.1z M19.7,5.1c0-0.5-0.4-0.9-0.9-0.9h-2.3c-0.5,0-0.9,0.4-0.9,0.9v2.1c0,0.5,0.4,0.9,0.9,0.9h2.3 c0.5,0,0.9-0.4,0.9-0.9L19.7,5.1L19.7,5.1z"></path>
        <foreignObject>Instagram</foreignObject>
      </switch>
    </svg>
    @azusahighschool
  </h2>
  -->
  <!--
  <p class="more">See more <a href="/news">news &amp; announcements</a></p>
  -->

  <a href="https://www.instagram.com">
    <img src="/images/photos/student-leadership.jpg" alt="" />
    <p>Student Leadership Class</p>
  </a>

  <a href="https://www.instagram.com" class="icon">
    <svg class="comment icon" viewBox="0 0 24 24" width="24" height="24">
      <path fill="white" d="M2.2,8.9c0,1,0.3,1.9,1,2.8c0.7,0.9,1.6,1.5,2.8,2c1.2,0.5,2.5,0.7,3.9,0.7c0.4,0,0.8,0,1.3-0.1c1.1,1,2.5,1.7,4,2.1
        c0.3,0.1,0.6,0.1,1,0.2c0.1,0,0.2,0,0.3-0.1c0.1-0.1,0.1-0.1,0.2-0.3v0c0,0,0-0.1,0-0.1c0,0,0-0.1,0-0.1c0,0,0,0,0-0.1L16.5,16
        c0,0,0,0-0.1-0.1c0,0-0.1-0.1-0.1-0.1c0,0-0.1-0.1-0.3-0.3c-0.1-0.2-0.2-0.3-0.3-0.3s-0.2-0.2-0.3-0.3c-0.1-0.2-0.2-0.3-0.3-0.4
        c-0.1-0.1-0.1-0.3-0.2-0.5s-0.2-0.4-0.2-0.7c0.9-0.5,1.6-1.2,2.1-1.9s0.8-1.6,0.8-2.4c0-0.8-0.2-1.5-0.6-2.2s-1-1.3-1.7-1.8
        S14,4.1,13,3.8s-2-0.4-3-0.4c-1.4,0-2.7,0.2-3.9,0.7S4,5.2,3.3,6.1S2.2,7.9,2.2,8.9z"></path>
    </svg>
    2
  </a>

  <a href="https://www.instagram.com" class="icon">
    <svg class="heart icon" viewBox="0 0 24 24" width="24" height="24">
      <path fill="white" d="M17.631 5.93c-0.394-0.913-1.185-1.682-2.281-2.158-0.968-0.422-2.012-0.471-2.96-0.214s-1.801 0.956-2.388 1.767c-0.588-0.811-1.44-1.511-2.389-1.767-0.949-0.258-1.991-0.207-2.96 0.214-1.096 0.476-1.885 1.243-2.281 2.158-0.394 0.912-0.397 1.974 0.103 3.027 1.062 2.257 7.494 7.55 7.529 7.64 0.033-0.090 6.466-5.383 7.53-7.64 0.498-1.053 0.496-2.115 0.101-3.027z"></path>
    </svg>
    115
  </a>
</div>

<div class="feature">
  <!--
  <h2>
    <svg class="icon" viewBox="0 0 24 24" width="48" height="48">
      <switch>
        <path fill="white" d="M22,19.4c0,1.4-1.2,2.6-2.6,2.6H4.6C3.2,22,2,20.8,2,19.4V4.6C2,3.2,3.2,2,4.6,2h14.9C20.8,2,22,3.2,22,4.6 V19.4z M19.7,10.5H18c0.2,0.5,0.3,1.1,0.3,1.7c0,3.3-2.8,6-6.2,6c-3.4,0-6.2-2.7-6.2-6c0-0.6,0.1-1.2,0.3-1.7H4.2v8.4 c0,0.4,0.4,0.8,0.8,0.8h13.9c0.4,0,0.8-0.4,0.8-0.8V10.5z M12,8.1c-2.2,0-4,1.7-4,3.9c0,2.1,1.8,3.9,4,3.9c2.2,0,4-1.7,4-3.9 C16,9.8,14.2,8.1,12,8.1z M19.7,5.1c0-0.5-0.4-0.9-0.9-0.9h-2.3c-0.5,0-0.9,0.4-0.9,0.9v2.1c0,0.5,0.4,0.9,0.9,0.9h2.3 c0.5,0,0.9-0.4,0.9-0.9L19.7,5.1L19.7,5.1z"></path>
        <foreignObject>Instagram</foreignObject>
      </switch>
    </svg>
    @azusahighschool
  </h2>
  -->
  <!--
  <p class="more">See more <a href="/news">news &amp; announcements</a></p>
  -->

  <a href="https://www.instagram.com">
    <img src="http://ahs-ausd-ca.schoolloop.com/uimg/file/1471331230544/2353954799496144620.jpg_wnp1000.jpg?1479224450531" alt="International Students from Japan visited Azusa High School" />
    <p>On November 9, forty International Students from Japan visited Azusa High School. They were able to experience how the American educational system in implemented. It was a great day for them to learn about our culture and it was even more exciting learning about their culture and educational system!</p>
  </a>

  <a href="https://www.instagram.com" class="icon">
    <svg class="comment icon" viewBox="0 0 24 24" width="24" height="24">
      <path fill="white" d="M2.2,8.9c0,1,0.3,1.9,1,2.8c0.7,0.9,1.6,1.5,2.8,2c1.2,0.5,2.5,0.7,3.9,0.7c0.4,0,0.8,0,1.3-0.1c1.1,1,2.5,1.7,4,2.1
        c0.3,0.1,0.6,0.1,1,0.2c0.1,0,0.2,0,0.3-0.1c0.1-0.1,0.1-0.1,0.2-0.3v0c0,0,0-0.1,0-0.1c0,0,0-0.1,0-0.1c0,0,0,0,0-0.1L16.5,16
        c0,0,0,0-0.1-0.1c0,0-0.1-0.1-0.1-0.1c0,0-0.1-0.1-0.3-0.3c-0.1-0.2-0.2-0.3-0.3-0.3s-0.2-0.2-0.3-0.3c-0.1-0.2-0.2-0.3-0.3-0.4
        c-0.1-0.1-0.1-0.3-0.2-0.5s-0.2-0.4-0.2-0.7c0.9-0.5,1.6-1.2,2.1-1.9s0.8-1.6,0.8-2.4c0-0.8-0.2-1.5-0.6-2.2s-1-1.3-1.7-1.8
        S14,4.1,13,3.8s-2-0.4-3-0.4c-1.4,0-2.7,0.2-3.9,0.7S4,5.2,3.3,6.1S2.2,7.9,2.2,8.9z"></path>
    </svg>
    2
  </a>

  <a href="https://www.instagram.com" class="icon">
    <svg class="heart icon" viewBox="0 0 24 24" width="24" height="24">
      <path fill="white" d="M17.631 5.93c-0.394-0.913-1.185-1.682-2.281-2.158-0.968-0.422-2.012-0.471-2.96-0.214s-1.801 0.956-2.388 1.767c-0.588-0.811-1.44-1.511-2.389-1.767-0.949-0.258-1.991-0.207-2.96 0.214-1.096 0.476-1.885 1.243-2.281 2.158-0.394 0.912-0.397 1.974 0.103 3.027 1.062 2.257 7.494 7.55 7.529 7.64 0.033-0.090 6.466-5.383 7.53-7.64 0.498-1.053 0.496-2.115 0.101-3.027z"></path>
    </svg>
    115
  </a>
</div>

<ul class="news-summary">
  <li>
    <a href="https://www.instagram.com">
      <img src="https://cdn.schoolloop.com/uimgcdn/aHR0cDovL2Focy1hdXNkLWNhLnNjaG9vbGxvb3AuY29tL3VpbWcvaW1hZ2UvMTMwMTc1MjUxMDEwNC8xNDcxMzMxMjMwNTQ0LzE0NzM5MjQ1NDk5NTQuanBnP2Nyb3BUb3A9MzMmY3JvcFJpZ2h0PTkwMCZjcm9wQm90dG9tPTYzMyZjcm9wTGVmdD05OSZiYXNpc1dpZHRoPTEwMDA=" alt="" />
      <span>2016 Homecoming</span>
    </a>

    <a href="https://www.instagram.com" class="icon">
      <svg class="comment icon" viewBox="0 0 24 24" width="24" height="24">
        <path fill="white" d="M2.2,8.9c0,1,0.3,1.9,1,2.8c0.7,0.9,1.6,1.5,2.8,2c1.2,0.5,2.5,0.7,3.9,0.7c0.4,0,0.8,0,1.3-0.1c1.1,1,2.5,1.7,4,2.1
          c0.3,0.1,0.6,0.1,1,0.2c0.1,0,0.2,0,0.3-0.1c0.1-0.1,0.1-0.1,0.2-0.3v0c0,0,0-0.1,0-0.1c0,0,0-0.1,0-0.1c0,0,0,0,0-0.1L16.5,16
          c0,0,0,0-0.1-0.1c0,0-0.1-0.1-0.1-0.1c0,0-0.1-0.1-0.3-0.3c-0.1-0.2-0.2-0.3-0.3-0.3s-0.2-0.2-0.3-0.3c-0.1-0.2-0.2-0.3-0.3-0.4
          c-0.1-0.1-0.1-0.3-0.2-0.5s-0.2-0.4-0.2-0.7c0.9-0.5,1.6-1.2,2.1-1.9s0.8-1.6,0.8-2.4c0-0.8-0.2-1.5-0.6-2.2s-1-1.3-1.7-1.8
          S14,4.1,13,3.8s-2-0.4-3-0.4c-1.4,0-2.7,0.2-3.9,0.7S4,5.2,3.3,6.1S2.2,7.9,2.2,8.9z"></path>
      </svg>
      2
    </a>

    <a href="https://www.instagram.com" class="icon">
      <svg class="heart icon" viewBox="0 0 24 24" width="24" height="24">
        <path fill="white" d="M17.631 5.93c-0.394-0.913-1.185-1.682-2.281-2.158-0.968-0.422-2.012-0.471-2.96-0.214s-1.801 0.956-2.388 1.767c-0.588-0.811-1.44-1.511-2.389-1.767-0.949-0.258-1.991-0.207-2.96 0.214-1.096 0.476-1.885 1.243-2.281 2.158-0.394 0.912-0.397 1.974 0.103 3.027 1.062 2.257 7.494 7.55 7.529 7.64 0.033-0.090 6.466-5.383 7.53-7.64 0.498-1.053 0.496-2.115 0.101-3.027z"></path>
      </svg>
      115
    </a>
  </li>
  <li>
    <a href="https://www.instagram.com">
      <img src="https://cdn.schoolloop.com/uimgcdn/aHR0cDovL2Focy1hdXNkLWNhLnNjaG9vbGxvb3AuY29tL3VpbWcvaW1hZ2UvMTMwMTc1MjUxMDEwNC8xNDcxMzMxMjMwNTQ0LzE0NzM0MDUzODYzMDAuanBnP2Nyb3BUb3A9MzImY3JvcFJpZ2h0PTkwMSZjcm9wQm90dG9tPTQ3OCZjcm9wTGVmdD0zMDYmYmFzaXNXaWR0aD0xMDAw" />
      <span>Aztec Cheer</span>
    </a>

    <a href="https://www.instagram.com" class="icon">
      <svg class="comment icon" viewBox="0 0 24 24" width="24" height="24">
        <path fill="white" d="M2.2,8.9c0,1,0.3,1.9,1,2.8c0.7,0.9,1.6,1.5,2.8,2c1.2,0.5,2.5,0.7,3.9,0.7c0.4,0,0.8,0,1.3-0.1c1.1,1,2.5,1.7,4,2.1
          c0.3,0.1,0.6,0.1,1,0.2c0.1,0,0.2,0,0.3-0.1c0.1-0.1,0.1-0.1,0.2-0.3v0c0,0,0-0.1,0-0.1c0,0,0-0.1,0-0.1c0,0,0,0,0-0.1L16.5,16
          c0,0,0,0-0.1-0.1c0,0-0.1-0.1-0.1-0.1c0,0-0.1-0.1-0.3-0.3c-0.1-0.2-0.2-0.3-0.3-0.3s-0.2-0.2-0.3-0.3c-0.1-0.2-0.2-0.3-0.3-0.4
          c-0.1-0.1-0.1-0.3-0.2-0.5s-0.2-0.4-0.2-0.7c0.9-0.5,1.6-1.2,2.1-1.9s0.8-1.6,0.8-2.4c0-0.8-0.2-1.5-0.6-2.2s-1-1.3-1.7-1.8
          S14,4.1,13,3.8s-2-0.4-3-0.4c-1.4,0-2.7,0.2-3.9,0.7S4,5.2,3.3,6.1S2.2,7.9,2.2,8.9z"></path>
      </svg>
      2
    </a>

    <a href="https://www.instagram.com" class="icon">
      <svg class="heart icon" viewBox="0 0 24 24" width="24" height="24">
        <path fill="white" d="M17.631 5.93c-0.394-0.913-1.185-1.682-2.281-2.158-0.968-0.422-2.012-0.471-2.96-0.214s-1.801 0.956-2.388 1.767c-0.588-0.811-1.44-1.511-2.389-1.767-0.949-0.258-1.991-0.207-2.96 0.214-1.096 0.476-1.885 1.243-2.281 2.158-0.394 0.912-0.397 1.974 0.103 3.027 1.062 2.257 7.494 7.55 7.529 7.64 0.033-0.090 6.466-5.383 7.53-7.64 0.498-1.053 0.496-2.115 0.101-3.027z"></path>
      </svg>
      115
    </a>
  </li>
  <li>
    <iframe src="https://drive.google.com/a/azusa.org/file/d/0B8uKDks0PtIVb2F6cERuR2FRMkU/preview" width="460" height="320"></iframe>
    <span>2016 Graduation was amazing!</span>

    <a href="https://www.instagram.com" class="icon">
      <svg class="comment icon" viewBox="0 0 24 24" width="24" height="24">
        <path fill="white" d="M2.2,8.9c0,1,0.3,1.9,1,2.8c0.7,0.9,1.6,1.5,2.8,2c1.2,0.5,2.5,0.7,3.9,0.7c0.4,0,0.8,0,1.3-0.1c1.1,1,2.5,1.7,4,2.1
          c0.3,0.1,0.6,0.1,1,0.2c0.1,0,0.2,0,0.3-0.1c0.1-0.1,0.1-0.1,0.2-0.3v0c0,0,0-0.1,0-0.1c0,0,0-0.1,0-0.1c0,0,0,0,0-0.1L16.5,16
          c0,0,0,0-0.1-0.1c0,0-0.1-0.1-0.1-0.1c0,0-0.1-0.1-0.3-0.3c-0.1-0.2-0.2-0.3-0.3-0.3s-0.2-0.2-0.3-0.3c-0.1-0.2-0.2-0.3-0.3-0.4
          c-0.1-0.1-0.1-0.3-0.2-0.5s-0.2-0.4-0.2-0.7c0.9-0.5,1.6-1.2,2.1-1.9s0.8-1.6,0.8-2.4c0-0.8-0.2-1.5-0.6-2.2s-1-1.3-1.7-1.8
          S14,4.1,13,3.8s-2-0.4-3-0.4c-1.4,0-2.7,0.2-3.9,0.7S4,5.2,3.3,6.1S2.2,7.9,2.2,8.9z"></path>
      </svg>
      2
    </a>

    <a href="https://www.instagram.com" class="icon">
      <svg class="heart icon" viewBox="0 0 24 24" width="24" height="24">
        <path fill="white" d="M17.631 5.93c-0.394-0.913-1.185-1.682-2.281-2.158-0.968-0.422-2.012-0.471-2.96-0.214s-1.801 0.956-2.388 1.767c-0.588-0.811-1.44-1.511-2.389-1.767-0.949-0.258-1.991-0.207-2.96 0.214-1.096 0.476-1.885 1.243-2.281 2.158-0.394 0.912-0.397 1.974 0.103 3.027 1.062 2.257 7.494 7.55 7.529 7.64 0.033-0.090 6.466-5.383 7.53-7.64 0.498-1.053 0.496-2.115 0.101-3.027z"></path>
      </svg>
      115
    </a>
  </li>
</ul>
