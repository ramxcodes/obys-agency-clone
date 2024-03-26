# Clone of Obys Agency

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation / Fork](#installation--fork)
- [Star the GitHub Repo](#star-the-github-repo)
- [Code of the Website](#code-of-the-website)

## Introduction
This project is a clone of Obys Agency, featuring a website with captivating animations created using various libraries like gsap, scrolltrigger, sheryjs, and locomotive.

<img src="https://drive.google.com/uc?export=view&id=1a7C0oVLDdWrdNZBrtWJLCb7yVN03CRvC" alt="Gojo Satoru Image" style="width: 100%; max-width: 600px; height: auto; margin: 20px 0;">
<a target="_blank" href="https://ramxcodes.github.io/obys-agency-clone/" target="_blank" style="display: inline-block; padding: 10px 20px; background-color: #3498db; color: #fff; text-decoration: none; border-radius: 5px; font-weight: bold; font-size: 16px; margin-bottom: 20px;">Visit Website ↗</a>

---

## Features
- Captivating animations throughout the website
- Utilization of GSAP for smooth animations
- Scrolltrigger for triggering animations based on scroll position
- Sheryjs for additional animation effects
- Locomotive for smooth scrolling experience

## Installation / Fork
To fork or clone this project, follow these steps:
1. Clone the repository to your local machine using:
   ```
   git clone https://github.com/ramxcodes/obys-agency-clone.git
   ```
2. Navigate into the cloned directory:
   ```
   cd obys-agency-clone
   ```
3. Start working on the project!

## Star the GitHub Repo
Don't forget to star the GitHub repository if you find this project interesting or useful!

## Code of the Website
The code of the website is available in the repository. Feel free to explore and modify it to suit your needs.

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Obys Agency</title>
    <link rel="shortcut icon" href="./assets/favicon.png" type="image/x-icon">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/locomotive-scroll@3.5.4/dist/locomotive-scroll.css">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/aayushchouhan24/sheryjs@main/dist/Shery.css" />
    <link href="https://cdn.jsdelivr.net/npm/remixicon@3.5.0/fonts/remixicon.css" rel="stylesheet">
    <link rel="stylesheet" href="style.css">
</head>

<body>

    <div id="loader">
        <div class="line">
            <div id="line1-part1">
                <h5>00</h5>
                <h6>- 100</h6>
            </div>
            <h1>Your</h1>
        </div>
        <div class="line">
            <h1>Web Experiences</h1>
        </div>
        <div class="line">
            <h1>is loading right</h1>
            <h2>Now</h2>
        </div>
    </div>
    <div id="main">
        <div id="page1" data-scroll data-scroll-speed="-1">
            <div id="nav">
                <svg class="brand__svg" width="71" height="27" viewBox="0 0 71 27">
                    <path
                        d="M40.7622 24.5917C40.7622 23.6724 41.4511 22.9829 42.3697 22.9829C43.2883 22.9829 43.9773 23.6724 43.9773 24.5917C43.9773 25.511 43.2883 26.2005 42.3697 26.2005C41.566 26.2005 40.7622 25.3961 40.7622 24.5917Z"
                        fill="currentColor"></path>
                    <path
                        d="M65.7937 8.96329C65.7937 8.04398 66.4826 7.35449 67.4012 7.35449C68.3198 7.35449 69.0087 8.04398 69.0087 8.96329C69.0087 9.88261 68.3198 10.5721 67.4012 10.5721C66.4826 10.5721 65.7937 9.88261 65.7937 8.96329Z"
                        fill="currentColor"></path>
                    <path
                        d="M59.019 18.3861C59.019 17.4668 59.708 16.7773 60.6266 16.7773C61.5451 16.7773 62.2341 17.4668 62.2341 18.3861C62.2341 19.3055 61.5451 19.9949 60.6266 19.9949C59.8228 19.9949 59.019 19.3055 59.019 18.3861Z"
                        fill="currentColor"></path>
                    <path
                        d="M41.3365 9.88276C40.5327 8.27396 39.6142 7.8143 39.04 7.58447H46.3887C45.9294 7.8143 45.0108 8.04413 45.0108 8.96344C45.0108 9.19327 45.1257 9.65293 45.3553 10.1126L48.3407 16.6627L46.5035 20.225L41.3365 9.88276Z"
                        fill="currentColor"></path>
                    <path
                        d="M51.8998 9.30819C51.8998 8.04413 50.9812 7.69939 50.2922 7.58447H54.6555C53.8517 7.8143 52.8183 8.27396 51.7849 10.1126C51.8998 9.88276 51.8998 9.65293 51.8998 9.30819Z"
                        fill="currentColor"></path>
                    <path
                        d="M66.7122 17.9266C66.7122 16.2029 65.2195 15.6283 63.0378 14.5941C60.8562 13.5599 59.019 12.7555 59.019 10.8019C59.019 8.73348 60.971 7.12468 64.1861 7.00977C63.1527 7.23959 62.3489 8.15891 62.3489 9.42296C62.3489 10.9168 63.612 11.4914 65.9084 12.5256C68.2049 13.5599 70.2717 14.4792 70.2717 16.6626C70.2717 19.1907 67.4011 20.3398 64.6454 20.4547C65.9084 20.2249 66.7122 19.1907 66.7122 17.9266Z"
                        fill="currentColor"></path>
                    <path
                        d="M21.0129 2.64303C21.0129 1.6088 20.3239 0.919313 19.2905 0.689485L24.4576 0V20.3398C24.4576 20.3398 22.6204 20.4547 20.8981 21.8337V2.64303H21.0129Z"
                        fill="currentColor"></path>
                    <path
                        d="M34.6764 14.0195C34.6764 10.4572 31.691 7.58432 27.9019 7.35449C30.1983 7.69923 30.8873 11.4914 30.8873 14.0195C30.8873 16.5476 30.1983 20.2249 27.9019 20.6845C31.8058 20.4547 34.6764 17.5819 34.6764 14.0195Z"
                        fill="currentColor"></path>
                    <path
                        d="M14.9269 14.0195C14.9269 10.4572 11.9415 7.58432 8.15234 7.35449C10.4488 7.69923 11.1377 11.4914 11.1377 14.0195C11.1377 16.5476 10.4488 20.2249 8.15234 20.6845C11.9415 20.4547 14.9269 17.5819 14.9269 14.0195Z"
                        fill="currentColor"></path>
                    <path
                        d="M0 14.0195C0 10.4572 2.9854 7.58432 6.77456 7.35449C4.4781 7.69923 3.78916 11.4914 3.78916 14.0195C3.78916 16.5476 4.4781 20.2249 6.77456 20.6845C2.9854 20.4547 0 17.5819 0 14.0195Z"
                        fill="currentColor"></path>
                </svg>
                <div id="nav-part2">
                    <h4>Works</h4>
                    <h4>About</h4>
                    <h4>Contacts</h4>
                </div>
            </div>
            <div class="hero" id="hero1">
                <h1>We Design</h1>
            </div>
            <div class="hero" id="hero2">
                <h1>Unique</h1>
            </div>
            <div class="hero" id="hero3">
                <h2>Web/</h2>
                <h2>Graphic</h2>
            </div>
            <div class="hero" id="hero4">
                <h1>Experience</h1>
            </div>
            <img id="flag" src="https://obys.agency/wp-content/uploads/2022/03/Flag.jpg" alt="">
        </div>
        <div id="page2" data-scroll data-scroll-speed="-2.5">
            <div id="video-container">
                <div id="video-cursor">
                    <i class="ri-play-mini-fill"></i>
                </div>
                <video loop src="https://obys.agency/wp-content/uploads/2022/11/Obys-Showreel-2022.mp4"></video>
            </div>
        </div>
        <div id="page3" data-scroll data-scroll-speed="-2.5">
            <h1>OUR PROJECTS</h1>
            <div class="underline"></div>
            <div id="image-div-container">
                <div class="image-div">
                    <img src="https://raw.githubusercontent.com/ramxcodes/obys-agency-clone/main/Assets/img/img1-1.jpg" alt="">
                    <img src="https://raw.githubusercontent.com/ramxcodes/obys-agency-clone/main/Assets/img/img1-2.jpg" alt="">
                </div>
                <div class="image-div">
                    <img src="https://raw.githubusercontent.com/ramxcodes/obys-agency-clone/main/Assets/img/img2-1.jpg" alt="">
                    <img src="https://raw.githubusercontent.com/ramxcodes/obys-agency-clone/main/Assets/img/img2-2.jpg" alt="">
                </div>
                <div class="page3-circle1">
                    <svg class="button__arrow" viewBox="0 0 91 118" fill="none">
                        <path
                            d="M15.2307 57.4152L15.9378 56.708L15.2307 56.0009L14.5236 56.708L15.2307 57.4152ZM34.9813 77.1658L34.2742 77.8729L35.9813 79.58L35.9813 77.1658L34.9813 77.1658ZM0.151478 72.4944L-0.555622 71.7873L-1.26273 72.4944L-0.555622 73.2015L0.151478 72.4944ZM45.29 117.633L44.5828 118.34L45.29 119.047L45.9971 118.34L45.29 117.633ZM60.3692 102.554L61.0763 103.261L61.7839 102.553L61.0758 101.846L60.3692 102.554ZM60.3685 102.553L59.6614 101.846L58.9538 102.553L59.6619 103.261L60.3685 102.553ZM90.427 72.4944L91.1341 73.2015L91.8412 72.4944L91.1341 71.7873L90.427 72.4944ZM75.3478 57.4152L76.0549 56.7081L75.3478 56.001L74.6407 56.7081L75.3478 57.4152ZM56.3065 76.4565L55.3065 76.4565L55.3065 78.8707L57.0136 77.1636L56.3065 76.4565ZM56.3065 0.120074L57.3065 0.120074L57.3065 -0.879926L56.3065 -0.879926L56.3065 0.120074ZM34.9813 0.120076L34.9813 -0.879924L33.9813 -0.879924L33.9813 0.120076L34.9813 0.120076ZM14.5236 58.1223L34.2742 77.8729L35.6884 76.4587L15.9378 56.708L14.5236 58.1223ZM0.858585 73.2015L15.9378 58.1223L14.5236 56.708L-0.555622 71.7873L0.858585 73.2015ZM45.9971 116.926L0.858585 71.7873L-0.555622 73.2015L44.5828 118.34L45.9971 116.926ZM59.662 101.846L44.5828 116.926L45.9971 118.34L61.0763 103.261L59.662 101.846ZM59.6619 103.261L59.6625 103.261L61.0758 101.846L61.0751 101.845L59.6619 103.261ZM61.0756 103.26L91.1341 73.2015L89.7199 71.7873L59.6614 101.846L61.0756 103.26ZM91.1341 71.7873L76.0549 56.7081L74.6407 58.1223L89.7199 73.2015L91.1341 71.7873ZM74.6407 56.7081L55.5994 75.7494L57.0136 77.1636L76.0549 58.1223L74.6407 56.7081ZM57.3065 76.4565L57.3065 0.120074L55.3065 0.120074L55.3065 76.4565L57.3065 76.4565ZM56.3065 -0.879926L34.9813 -0.879924L34.9813 1.12008L56.3065 1.12007L56.3065 -0.879926ZM33.9813 0.120076L33.9813 77.1658L35.9813 77.1658L35.9813 0.120076L33.9813 0.120076Z"
                            fill="currentColor"></path>
                    </svg>
                    <div class="circle-in">
                        <p>We are thrilled to have you on board. We hove you enjoyed the projects ❤</p>
                    </div>
                </div>
                <div class="page3-circle2">
                    <svg class="button__arrow" viewBox="0 0 91 118" fill="none">
                        <path
                            d="M15.2307 57.4152L15.9378 56.708L15.2307 56.0009L14.5236 56.708L15.2307 57.4152ZM34.9813 77.1658L34.2742 77.8729L35.9813 79.58L35.9813 77.1658L34.9813 77.1658ZM0.151478 72.4944L-0.555622 71.7873L-1.26273 72.4944L-0.555622 73.2015L0.151478 72.4944ZM45.29 117.633L44.5828 118.34L45.29 119.047L45.9971 118.34L45.29 117.633ZM60.3692 102.554L61.0763 103.261L61.7839 102.553L61.0758 101.846L60.3692 102.554ZM60.3685 102.553L59.6614 101.846L58.9538 102.553L59.6619 103.261L60.3685 102.553ZM90.427 72.4944L91.1341 73.2015L91.8412 72.4944L91.1341 71.7873L90.427 72.4944ZM75.3478 57.4152L76.0549 56.7081L75.3478 56.001L74.6407 56.7081L75.3478 57.4152ZM56.3065 76.4565L55.3065 76.4565L55.3065 78.8707L57.0136 77.1636L56.3065 76.4565ZM56.3065 0.120074L57.3065 0.120074L57.3065 -0.879926L56.3065 -0.879926L56.3065 0.120074ZM34.9813 0.120076L34.9813 -0.879924L33.9813 -0.879924L33.9813 0.120076L34.9813 0.120076ZM14.5236 58.1223L34.2742 77.8729L35.6884 76.4587L15.9378 56.708L14.5236 58.1223ZM0.858585 73.2015L15.9378 58.1223L14.5236 56.708L-0.555622 71.7873L0.858585 73.2015ZM45.9971 116.926L0.858585 71.7873L-0.555622 73.2015L44.5828 118.34L45.9971 116.926ZM59.662 101.846L44.5828 116.926L45.9971 118.34L61.0763 103.261L59.662 101.846ZM59.6619 103.261L59.6625 103.261L61.0758 101.846L61.0751 101.845L59.6619 103.261ZM61.0756 103.26L91.1341 73.2015L89.7199 71.7873L59.6614 101.846L61.0756 103.26ZM91.1341 71.7873L76.0549 56.7081L74.6407 58.1223L89.7199 73.2015L91.1341 71.7873ZM74.6407 56.7081L55.5994 75.7494L57.0136 77.1636L76.0549 58.1223L74.6407 56.7081ZM57.3065 76.4565L57.3065 0.120074L55.3065 0.120074L55.3065 76.4565L57.3065 76.4565ZM56.3065 -0.879926L34.9813 -0.879924L34.9813 1.12008L56.3065 1.12007L56.3065 -0.879926ZM33.9813 0.120076L33.9813 77.1658L35.9813 77.1658L35.9813 0.120076L33.9813 0.120076Z"
                            fill="currentColor"></path>
                    </svg>
                    <div class="circle-in">
                        <p>We are thrilled to have you on board. We hove you enjoyed the projects</p>
                    </div>
                </div>
                <div class="image-div">
                    <img src="https://raw.githubusercontent.com/ramxcodes/obys-agency-clone/main/Assets/img/img3-1.jpg" alt="">
                    <img src="https://raw.githubusercontent.com/ramxcodes/obys-agency-clone/main/Assets/img/img3-2.jpg" alt="">
                </div>
                <div class="image-div">
                    <img src="https://raw.githubusercontent.com/ramxcodes/obys-agency-clone/main/Assets/img/img4-1.jpg" alt="">
                    <img src="https://raw.githubusercontent.com/ramxcodes/obys-agency-clone/main/Assets/img/img4-2.jpg" alt="">
                </div>
            </div>
        </div>
        <div id="page4" data-scroll data-scroll-speed="2.5">
            <div id="page4-content">
                <h1>About Obys</h1>
                <div class="underline"></div>
                <p>Our
                    agency
                    is
                    about
                    people
                    who
                    love

                    creating,
                    designing
                    and
                    developing

                    wow
                    projects.
                    In
                    the
                    same
                    time
                    we

                    are
                    a
                    boutique
                    agency
                    that
                    is
                    more

                    than
                    the
                    collective.
                    We
                    learn
                    and

                    grow,
                    win
                    and
                    celebrate
                    together. </p>
                <div id="page4-flex">
                    <img src="https://obys.agency/wp-content/uploads/2020/07/content-image01.jpg" alt="">
                    <p>
                        We are happy to present our new website and updated version of Obys agency. As before we are
                        open for new projects worldwide!
                        <br><br>
                        Would you like to have award winning site or unique branding style, please say hi to our manager
                        —info@obys.agency.
                        And we will help you with the pleasure.

                    </p>
                </div>
                <div id="page4-blue-div">
                    <div class="blue-div-elem">
                        <h4>Awwwards x16</h4>
                        <p>SOTM, SOTD and Honrable Mentions</p>
                    </div>
                    <div class="blue-div-elem">
                        <h4>FWA x11</h4>
                        <p>FWA of The Day</p>
                    </div>
                    <div class="blue-div-elem">
                        <h4>CSSDA x23</h4>
                        <p>WOTM, WOTD and UI, UX, Innovation</p>
                    </div>
                    <div class="blue-div-elem">
                        <h4>Behance x25</h4>
                        <p>Interaction, Graphic Design</p>
                    </div>
                    <div class="blue-div-elem">
                        <h4>The Very Best Of x7</h4>
                        <p>The Very Best Of, Best Of</p>
                    </div>
                </div>
                <div class="underline"></div>

            </div>
        </div>
        <div id="page5" data-scroll data-scroll-speed="-2.5">
            <div class="elem">
                <h1><span>Sport</span> - Fasion - Technology -</h1>
                <h1><span>Sport</span> - Fasion - Technology -</h1>
            </div>
            <div class="elem2">
                <h1>Science - <span>partners</span> - Travel -</h1>
                <h1>Science - <span>partners</span> - Travel -</h1>
            </div>
            <div class="elem">
                <h1>Sport - Fasion - <span>Technology</span> -</h1>
                <h1>Sport - Fasion - <span>Technology</span> -</h1>
            </div>
            <div class="elem2">
                <h1><span>Science</span> - partners - Travel -</h1>
                <h1><span>Science</span> - partners - Travel -</h1>
            </div>
        </div>
        <div id="footer" data-scroll data-scroll-speed="-2.5">
            <div id="footer-text">
                <h1>Let's Create</h1>
                <h2>Let's Create</h1>

            </div>
            <div class="underline"></div>
            <div id="footer-div">
                <div class="box">
                    <h6>Socials</h6>
                    <h5>Dribbble</h5>
                    <h5>Behance</h5>
                    <h5>Instagram</h5>
                    <h5>Facebook</h5>
                    <h5>Twitter</h5>
                    <h5>YouTube</h5>
                </div>
                <div class="box">
                    <h6>Address</h6>
                    <h5>Pushkinska 5
                        61057 Kharkiv
                        Ukraine</h5>

                </div>
                <div class="box">
                    <h6>Say Hi!</h6>
                    <h5>info@obys.agency</h5>
                </div>
            </div>
            <div class="underline"></div>
            <h5>Obys Agency © 2024   Made with ❤️ <a target="_blank" href="https://github.com/ramxcodes"> Ram</a></h5>
        </div>
    </div>

    <script src="https://cdn.jsdelivr.net/npm/locomotive-scroll@3.5.4/dist/locomotive-scroll.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.2/gsap.min.js"
        integrity="sha512-16esztaSRplJROstbIIdwX3N97V1+pZvV33ABoG1H2OyTttBxEGkTsoIVsiP1iaTtM8b3+hu2kB6pQ4Clr5yug=="
        crossorigin="anonymous" referrerpolicy="no-referrer"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.2/ScrollTrigger.min.js"
        integrity="sha512-Ic9xkERjyZ1xgJ5svx3y0u3xrvfT/uPkV99LBwe68xjy/mGtO+4eURHZBW2xW4SZbFrF1Tf090XqB+EVgXnVjw=="
        crossorigin="anonymous" referrerpolicy="no-referrer"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/three.js/0.155.0/three.min.js"></script>
    <script src="https://cdn.jsdelivr.net/gh/automat/controlkit.js@master/bin/controlKit.min.js"></script>
    <script type="text/javascript"
        src="https://cdn.jsdelivr.net/gh/aayushchouhan24/sheryjs@main/dist/Shery.js"></script>
    <script src="script.js"></script>
</body>

</html>
```

### CSS (style.css)

```css
@font-face {
    font-family: "Plain Light";
    src: url(./fonts/plain-regular-webfont.ttf);
}

@font-face {
    font-family: "Plain Light";
    src: url(./fonts/plain-light-webfont.ttf);
}

@font-face {
    font-family: "silk serif";
    src: url(./fonts/silkserif-regularitalic-webfont.ttf);
}

@font-face {
    font-family: "silk serif";
    src: url(./fonts/silkserif-lightitalic-webfont.ttf);
}

* {
    margin: 0;
    padding: 0;
    -webkit-box-sizing: border-box;
            box-sizing: border-box;
    font-family: "Plain Light";
    color: #fff;
}

html,
body {
    height: 100%;
    width: 100%;
}

body {
    overflow-x: hidden;
}

.mousefollower {
    border: 2px solid #fff;
    background-color: rgb(255, 255, 255);
    scale: 2;
    mix-blend-mode: difference;
}

#loader {
    height: 100%;
    width: 100%;
    position: fixed;
    z-index: 9999;
    background-color: #030303;
    padding: 25vh 10vw;
}

.line {
    /* background-color: red; */
    height: -webkit-fit-content;
    height: -moz-fit-content;
    height: fit-content;
    overflow: hidden;
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-align: center;
        -ms-flex-align: center;
            align-items: center;
    -webkit-box-pack: start;
        -ms-flex-pack: start;
            justify-content: flex-start;
    gap: 3vw;
}

#line1-part1 {
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-align: center;
        -ms-flex-align: center;
            align-items: center;
    -webkit-box-pack: center;
        -ms-flex-pack: center;
            justify-content: center;
    gap: 1vw;

}

#line1-part1 h5,
#line1-part1 h6 {
    font-size: 3vw;
    font-weight: 100;
    font-family: 'silk serif';
}

#line1-part1 h5 {
    /* background-color: red; */
    width: 5vw;
    text-align: right;
}

.line h1 {
    font-size: 6.5vw;
    text-transform: uppercase;
    font-weight: 900;
}

.line h2 {
    font-size: 5vw;
    text-transform: uppercase;
    font-weight: 900;
    opacity: 0;
    /* animation-name: loaderAnim */
    -webkit-animation-duration: 2s;
            animation-duration: 2s;
    -webkit-animation-iteration-count: infinite;
            animation-iteration-count: infinite;
}

@-webkit-keyframes loaderAnime {
    0% {
        font-family: "plain light";
        -webkit-text-stroke: 1px #fff;
        color: #fff;
        font-weight: 500;
        opacity: 1;
    }

    48% {
        font-family: "plain light";
        -webkit-text-stroke: 1px #fff;
        color: #fff;
        font-weight: 500;
        opacity: 0;
    }

    50% {
        font-family: 'silk serif';
        -webkit-text-stroke: 1px #fff;
        font-weight: 500;
        color: transparent;
        opacity: 1;
    }

    100% {
        font-family: 'silk serif';
        -webkit-text-stroke: 1px #fff;
        font-weight: 500;
        color: transparent;
        opacity: 0;
    }
}

@keyframes loaderAnime {
    0% {
        font-family: "plain light";
        -webkit-text-stroke: 1px #fff;
        color: #fff;
        font-weight: 500;
        opacity: 1;
    }

    48% {
        font-family: "plain light";
        -webkit-text-stroke: 1px #fff;
        color: #fff;
        font-weight: 500;
        opacity: 0;
    }

    50% {
        font-family: 'silk serif';
        -webkit-text-stroke: 1px #fff;
        font-weight: 500;
        color: transparent;
        opacity: 1;
    }

    100% {
        font-family: 'silk serif';
        -webkit-text-stroke: 1px #fff;
        font-weight: 500;
        color: transparent;
        opacity: 0;
    }
}





#main {
    position: relative;
    background-color: #151515;
    z-index: 99;
}

#page1 {
    height: 100vh;
    width: 100%;
    /* background-color: #151515; */
    position: relative;
    z-index: 100;
}

#page1 #nav {
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-align: center;
        -ms-flex-align: center;
            align-items: center;
    -webkit-box-pack: justify;
        -ms-flex-pack: justify;
            justify-content: space-between;
    padding: 2.3vw 5.5vw;
}

#nav-part2 {
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-align: center;
        -ms-flex-align: center;
            align-items: center;
    -webkit-box-pack: center;
        -ms-flex-pack: center;
            justify-content: center;
    gap: 3vw;
}

#nav-part2 h4 {
    font-size: 0.8vw;
    font-weight: 500;
}

.hero {
    /* background-color: red; */
    width: 72%;
    margin-left: 27%;
    height: -webkit-fit-content;
    height: -moz-fit-content;
    height: fit-content;
    /* background-color: red; */
    overflow-y: hidden;
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-align: center;
        -ms-flex-align: center;
            align-items: center;


}



.hero:nth-child(2) {
    margin-top: 18vh;
}

.hero h1 {
    font-size: 7.2vw;
    font-weight: 600;
    text-transform: uppercase;
    line-height: 7.2vw;
    position: relative;
}

#hero1::before {
    content: "01";
    position: absolute;
    font-size: 3vw;
    font-weight: 100;
    font-family: "silk serif";
    left: 20%;
    top: 29%;
}

.hero h2 {
    font-size: 7.2vw;
    font-weight: 600;
    text-transform: uppercase;
    line-height: 7.2vw;
    border-bottom: 0.5vw solid #fff;
    /* padding-bottom: 0.8vw;
    /* transition: all ease 0.3s; */

}

.hero h2:hover {
    -webkit-text-stroke: 2px #fff;
    color: transparent;
    font-weight: 500;
    border-bottom: 0.5vw solid #ffffff00;
}

#page2 {
    height: 100vh;
    width: 100%;
    padding-top: 17vh;
    position: relative;
}

#video-container {
    height: 66vh;
    width: 71vw;
    position: relative;
    left: 28%;
    background-color: red;
    background-image: url(https://obys.agency/wp-content/uploads/2022/11/Showreel-2022-preview-1.jpg);
    background-size: cover;
    background-position: center;
}

#video-container video {
    height: 100%;
    width: 100%;
    -o-object-fit: cover;
       object-fit: cover;
    opacity: 0;
}


#video-cursor {
    background-color: #FFA63D;
    height: 9vw;
    width: 9vw;
    border-radius: 50%;
    position: absolute;
    top: -15%;
    left: 70%;
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-align: center;
        -ms-flex-align: center;
            align-items: center;
    -webkit-box-pack: center;
        -ms-flex-pack: center;
            justify-content: center;
    z-index: 999;
}

#video-cursor i {
    font-size: 2vw;
}

#page3 {
    min-height: 100vh;
    width: 100%;
    /* background-color: rgb(61, 61, 61); */
    position: relative;
    padding: 17vh 2vw;
    margin-bottom: 20vh;
    margin-top: 20vh;
}

#page3 h1 {
    font-size: 7vw;
    text-transform: uppercase;
    position: relative;
    margin-left: 28vw;
}

#page3 h1::before {
    content: "02";
    position: absolute;
    font-size: 3vw;
    font-weight: 100;
    font-family: "silk serif";
    left: -12%;
    top: 8%;
}

#page3 .underline {
    margin-left: 28vw;

}

#image-div-container {
    /* background-color: red; */
    padding: 1vw;
    position: relative;
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-align: start;
        -ms-flex-align: start;
            align-items: flex-start;
    -webkit-box-pack: start;
        -ms-flex-pack: start;
            justify-content: flex-start;
    -ms-flex-wrap: wrap;
        flex-wrap: wrap;
}

.image-div {
    height: 42vw;
    width: 31vw;
    position: relative;
    overflow: hidden;
    -ms-flex-negative: 0;
        flex-shrink: 0;
    margin: 1vw;
    /* background-color: blue; */
}

.image-div:nth-child(1) {
    height: 29vw;
    width: 21vw;
}

.image-div img {
    height: 100%;
    width: 100%;
    -o-object-fit: cover;
       object-fit: cover;
    -o-object-position: center;
       object-position: center;
}

.page3-circle1 {
    height: 23vw;
    width: 23vw;
    border: 2px solid #fff;
    border-radius: 50%;
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    margin-top: 23vh;
    position: relative;
    -webkit-box-align: center;
        -ms-flex-align: center;
            align-items: center;
    -ms-flex-negative: 0;
        flex-shrink: 0;
    margin-left: 10vw;
    -webkit-box-pack: center;
        -ms-flex-pack: center;
            justify-content: center;
}

.page3-circle1 svg {
    height: 30%;
}

.page3-circle2 {
    height: 23vw;
    width: 23vw;
    border: 2px solid #fff;
    border-radius: 50%;
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    position: relative;
    /* margin-top: 23vh; */
    -ms-flex-negative: 0;
        flex-shrink: 0;
    -webkit-box-align: center;
        -ms-flex-align: center;
            align-items: center;
    /* margin-left: 10vw; */
    -webkit-box-pack: center;
        -ms-flex-pack: center;
            justify-content: center;
    margin-top: 2vw;
    margin-right: 3vw;
}

.page3-circle2 svg {
    height: 30%;
    rotate: -45deg;
}

.circle-in {
    height: 100%;
    width: 100%;
    position: absolute;
    top: 0;
    left: 0;
    background-color: #fff;
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-align: center;
        -ms-flex-align: center;
            align-items: center;
    -webkit-box-pack: center;
        -ms-flex-pack: center;
            justify-content: center;
    /* display: ; */
    -webkit-transition: all ease 0.5s;
    -o-transition: all ease 0.5s;
    transition: all ease 0.5s;
    scale: 0;
    border-radius: 50%;
}

.circle-in p {
    font-size: 0.95vw;
    color: #000;
    font-weight: 500;
    width: 60%;
    scale: 0;
    -webkit-transition: all ease 0.5s;
    -o-transition: all ease 0.5s;
    transition: all ease 0.5s;
    -webkit-transition-delay: 0.3s;
         -o-transition-delay: 0.3s;
            transition-delay: 0.3s;
    opacity: 0;
}

.page3-circle1:hover .circle-in {
    scale: 1;
}

.page3-circle1:hover p {
    scale: 1;
    opacity: 1;
}

.page3-circle2:hover .circle-in {
    scale: 1;
}

.page3-circle2:hover p {
    scale: 1;
    opacity: 1;
}




#page4 {
    min-height: 100vh;
    position: relative;
    width: 100%;
    /* background-color: rgb(61, 61, 61); */
    padding: 7vh 0;
}

#page4-content {
    width: 72vw;
    position: relative;

    margin-left: 28%;
}

#page4-content h1 {
    font-size: 7vw;
    text-transform: uppercase;
    position: relative;
}

#page4-content h1::before {
    content: "03";
    position: absolute;
    font-size: 3vw;
    font-weight: 100;
    font-family: "silk serif";
    left: -12%;
    top: 8%;
}

#page4-content .underline {
    height: 1px;
    width: 100%;
    background-color: #fff;
    margin: 5vw 0;
}

#page4-content > p {
    font-size: 2.05vw;
    width: 50%;
    margin-bottom: 3vw;
}

#page4-flex {
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
}

#page4-flex img {
    width: 48%;
}

#page4-flex p {
    font-size: 0.9vw;
    width: 19%;
    margin-left: 1vw;
}

#page4-blue-div {
    background-color: #3F7DF4;
    width: 33vw;
    padding: 3vw;
    position: relative;
    margin-top: -35vh;
    margin-left: 26vw;
}

.blue-div-elem {
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-align: start;
        -ms-flex-align: start;
            align-items: flex-start;
    -webkit-box-pack: justify;
        -ms-flex-pack: justify;
            justify-content: space-between;
    /* background-color: red; */
    padding: 1.7vw 0;
    border-bottom: 2px solid #ffffff94;
}

.blue-div-elem h4 {
    font-size: 1.4vw;
    font-weight: 500;
}

.blue-div-elem p {
    width: 40%;
    font-size: 0.8vw;
}

#page5 {
    min-height: 100vh;
    width: 100%;
    position: relative;
}

.elem {
    white-space: nowrap;
    overflow-x: hidden;
    margin-bottom: -2vw;
}

.elem h1 {
    font-size: 7vw;
    -webkit-text-stroke: 1px #fff;
    font-weight: 400;
    text-transform: uppercase;
    /* background-color: red; */
    color: transparent;
    display: inline-block;
    margin-right: 16px;
    -webkit-animation-name: anime;
            animation-name: anime;
    -webkit-animation-duration: 17s;
            animation-duration: 17s;
    -webkit-animation-timing-function: linear;
            animation-timing-function: linear;
    -webkit-animation-iteration-count: infinite;
            animation-iteration-count: infinite;
}

@-webkit-keyframes anime {
    from {
        -webkit-transform: translateX(0);
                transform: translateX(0);
    }

    to {
        -webkit-transform: translateX(calc(-100% - 20px));
                transform: translateX(calc(-100% - 20px));
    }
}

@keyframes anime {
    from {
        -webkit-transform: translateX(0);
                transform: translateX(0);
    }

    to {
        -webkit-transform: translateX(calc(-100% - 20px));
                transform: translateX(calc(-100% - 20px));
    }
}


.elem2 {
    white-space: nowrap;
    overflow-x: hidden;
    margin-bottom: -2vw;
}

.elem2 h1 {
    font-size: 7vw;
    -webkit-text-stroke: 1px #fff;
    font-weight: 400;
    text-transform: uppercase;
    /* background-color: red; */
    color: transparent;
    display: inline-block;
    -webkit-transform: translateX(calc(-100% - 20px));
        -ms-transform: translateX(calc(-100% - 20px));
            transform: translateX(calc(-100% - 20px));
    -webkit-animation-name: anime;
            animation-name: anime;
    -webkit-animation-duration: 18s;
            animation-duration: 18s;
    -webkit-animation-timing-function: linear;
            animation-timing-function: linear;
    -webkit-animation-iteration-count: infinite;
            animation-iteration-count: infinite;
    animation-direction: reverse;
}

.elem span {
    font-style: italic;
    font-family: "silk serif";
    color: transparent;
}

.elem2 span {
    font-style: italic;
    font-family: "silk serif";
    color: transparent;
}

#footer {
    height: 85vh;
    width: 100%;
    /* background-color: red; */
    position: relative;
    padding-left: 28vw;
    margin-top: 5vw;
    padding-right: 2vw;
}

#footer h1 {
    font-size: 7.2vw;
    text-transform: uppercase;
    /* background-color: blue; */
    position: relative;
}

#footer-text {
    position: relative;
    /* background-color: red; */
}

#footer-text h2 {
    font-size: 7.2vw;
    text-transform: uppercase;
    position: absolute;
    top: -10%;
    font-weight: 500;

    left: 0;
    font-family: "silk serif";
}

#footer-text h2 span {
    font-family: "silk serif";
    opacity: 0;
    -webkit-text-stroke: 1px #fff;
    color: transparent;
}

#footer-text::before {
    content: "04";
    position: absolute;
    font-size: 3vw;
    font-weight: 100;
    font-family: "silk serif";
    left: -13%;
    top: 6%;
}

.underline {
    height: 1px;
    width: 100%;
    background-color: #fff;
    margin: 3vw 0;
}

#footer-div {
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-align: start;
        -ms-flex-align: start;
            align-items: flex-start;
    -webkit-box-pack: justify;
        -ms-flex-pack: justify;
            justify-content: space-between;
    padding-right: 15vw;
    padding-top: 4vw;
    margin-bottom: 6vw;
}

#footer-div h6 {
    font-size: 0.9vw;
    margin-bottom: 1.5vw;
    font-weight: 500;
}

.box {
    width: 20%;
}

#footer-div h5 {
    font-size: 1.4vw;
    font-weight: 500;
    /* margin: 0.1vh 0; */
}

#footer > h5 {
    font-weight: 500;
    font-size: 1vw;
}

#footer a{
    text-decoration: none;
}

._canvas_container {
    z-index: 999999 !important;
    pointer-events: none;
}

#flag {
    height: 25vw;
    position: absolute;
    top: 0;
    opacity: 0;

    left: 0;
    -webkit-transform: translate(-50%, -50%);
        -ms-transform: translate(-50%, -50%);
            transform: translate(-50%, -50%);
}

#hero3 {
    /* background-color: red; */
    z-index: 999;
    position: relative;
}


@media (max-width:600px) {

    #loader {
        height: 100%;
        width: 100%;
        position: fixed;
        z-index: 999999;
        background-color: #030303;
        padding: 25vh 5vw;
    }

    .line {
        /* background-color: red; */
        height: -webkit-fit-content;
        height: -moz-fit-content;
        height: fit-content;
        overflow: hidden;
        display: -webkit-box;
        display: -ms-flexbox;
        display: flex;
        -webkit-box-align: start;
            -ms-flex-align: start;
                align-items: flex-start;
        -webkit-box-pack: start;
            -ms-flex-pack: start;
                justify-content: flex-start;
        gap: 3vw;
        -webkit-box-orient: vertical;
        -webkit-box-direction: normal;
            -ms-flex-direction: column;
                flex-direction: column;
    }

    #line1-part1 {
        display: -webkit-box;
        display: -ms-flexbox;
        display: flex;
        -webkit-box-align: center;
            -ms-flex-align: center;
                align-items: center;
        -webkit-box-pack: center;
            -ms-flex-pack: center;
                justify-content: center;
        gap: 1vw;

    }

    #line1-part1 h5,
    #line1-part1 h6 {
        font-size: 4vw;
        font-weight: 100;
        font-family: 'silk serif';
    }

    #line1-part1 h5 {
        /* background-color: red; */
        width: 5vw;
        text-align: right;
    }

    .line h1 {
        font-size: 8.5vw;
        text-transform: uppercase;
        font-weight: 900;
    }

    .line h2 {
        font-size: 8vw;
        text-transform: uppercase;
        font-weight: 900;
        opacity: 0;
        /* animation-name: loaderAnim */
        -webkit-animation-duration: 2s;
                animation-duration: 2s;

        /* display: none; */
        -webkit-animation-iteration-count: infinite;
                animation-iteration-count: infinite;
    }

    #page1 {
        height: 60vh;
        width: 100%;
        /* background-color: #151515; */
        position: relative;
        z-index: 100;
        /* background-color: red; */
        padding-top: 1px;
    }

    #page1 #nav {
        display: -webkit-box;
        display: -ms-flexbox;
        display: flex;
        -webkit-box-align: center;
            -ms-flex-align: center;
                align-items: center;
        -webkit-box-pack: end;
            -ms-flex-pack: end;
                justify-content: flex-end;
        padding: 4.3vw 5vw;
        position: fixed;
        width: 100%;
        /* background-color: red; */
        top: 0;
    }

    #nav svg {
        scale: 0.8;
    }

    #nav-part2 {
        display: -webkit-box;
        display: -ms-flexbox;
        display: flex;
        -webkit-box-align: center;
            -ms-flex-align: center;
                align-items: center;
        -webkit-box-pack: center;
            -ms-flex-pack: center;
                justify-content: center;
        gap: 3vw;
        display: none;
    }

    #nav-part2 h4 {
        font-size: 0.8vw;
        font-weight: 500;

    }

    .hero {
        /* background-color: red; */
        width: 72%;
        margin-left: 5%;
        height: -webkit-fit-content;
        height: -moz-fit-content;
        height: fit-content;
        /* background-color: red; */
        overflow-y: hidden;
        display: -webkit-box;
        display: -ms-flexbox;
        display: flex;
        -webkit-box-align: center;
            -ms-flex-align: center;
                align-items: center;
    }



    .hero:nth-child(2) {
        margin-top: 25vh;
    }

    .hero h1 {
        font-size: 9.8vw;
        font-weight: 600;
        text-transform: uppercase;
        line-height: 10.5vw;
        position: relative;
    }

    #hero1::before {
        content: "01";
        position: absolute;
        font-size: 5vw;
        font-weight: 100;
        font-family: "silk serif";
        left: 5%;
        top: 35%;
    }

    .hero h2 {
        font-size: 9.8vw;
        font-weight: 600;
        text-transform: uppercase;
        line-height: 10.5vw;
        border-bottom: 0.6vw solid #fff;
    }

    #page2 {
        height: 58vh;
        width: 100%;
        padding-top: 6vh;
        position: relative;
    }

    #video-container {
        height: 52vh;
        width: 100vw;
        position: relative;
        left: 0%;
        background-color: red;
        background-image: url(https://obys.agency/wp-content/uploads/2022/11/Showreel-2022-preview-1.jpg);
        background-size: cover;
        background-position: center;
    }

    #video-container video {
        height: 100%;
        width: 100%;
        -o-object-fit: cover;
           object-fit: cover;
        opacity: 0;
    }


    #video-cursor {
        background-color: #FFA63D;
        height: 25vw;
        width: 25vw;
        border-radius: 50%;
        position: absolute;
        top: 50%;
        left: 50%;
        display: -webkit-box;
        display: -ms-flexbox;
        display: flex;
        -webkit-transform: translate(-50%, -50%);
            -ms-transform: translate(-50%, -50%);
                transform: translate(-50%, -50%);
        -webkit-box-align: center;
            -ms-flex-align: center;
                align-items: center;
        -webkit-box-pack: center;
            -ms-flex-pack: center;
                justify-content: center;
        z-index: 999;
    }

    #video-cursor i {
        font-size: 5vw;
    }

    #page3 {
        min-height: 100vh;
        width: 100%;
        /* background-color: rgb(61, 61, 61); */
        position: relative;
        padding: 17vh 3vw 0 3vw;
        margin-bottom: 0vh;
        margin-top: 0vh;
    }

    #page3 h1 {
        font-size: 9.5vw;
        text-transform: uppercase;
        position: relative;
        margin-left: 2vw;
        margin-bottom: 5vw;
    }

    #page3 h1::before {
        content: "02";
        position: absolute;
        font-size: 5vw;
        font-weight: 100;
        font-family: "silk serif";
        left: 0%;
        top: -66%;
    }

    #page3 .underline {
        margin-left: 2vw;
        width: 94%;

    }

    #image-div-container {
        /* background-color: red; */
        margin-top: 10vw;
        padding: 1vw;
        position: relative;
        display: -webkit-box;
        display: -ms-flexbox;
        display: flex;
        -webkit-box-align: start;
            -ms-flex-align: start;
                align-items: flex-start;
        -webkit-box-pack: start;
            -ms-flex-pack: start;
                justify-content: flex-start;
        -ms-flex-wrap: wrap;
            flex-wrap: wrap;
        -webkit-box-orient: vertical;
        -webkit-box-direction: normal;
            -ms-flex-direction: column;
                flex-direction: column;
    }

    .image-div {
        height: 110vw;
        width: 90vw;
        position: relative;
        overflow: hidden;
        -ms-flex-negative: 0;
            flex-shrink: 0;
        margin: 1vw;
        margin-bottom: 8vw;
        /* background-color: blue; */
    }

    .image-div:nth-child(1) {
        height: 110vw;
        width: 90vw;
    }

    .image-div img {
        height: 100%;
        width: 100%;
        -o-object-fit: cover;
           object-fit: cover;
        -o-object-position: center;
           object-position: center;
    }

    .page3-circle1 {
        height: 23vw;
        width: 23vw;
        border: 2px solid #fff;
        border-radius: 50%;
        display: -webkit-box;
        display: -ms-flexbox;
        display: flex;
        margin-top: 23vh;
        position: relative;
        -webkit-box-align: center;
            -ms-flex-align: center;
                align-items: center;
        -ms-flex-negative: 0;
            flex-shrink: 0;
        margin-left: 10vw;
        -webkit-box-pack: center;
            -ms-flex-pack: center;
                justify-content: center;
        display: none;

    }

    .page3-circle1 svg {
        height: 30%;
    }

    .page3-circle2 {
        height: 23vw;
        width: 23vw;
        border: 2px solid #fff;
        border-radius: 50%;
        display: -webkit-box;
        display: -ms-flexbox;
        display: flex;
        position: relative;
        /* margin-top: 23vh; */
        -ms-flex-negative: 0;
            flex-shrink: 0;
        -webkit-box-align: center;
            -ms-flex-align: center;
                align-items: center;
        /* margin-left: 10vw; */
        -webkit-box-pack: center;
            -ms-flex-pack: center;
                justify-content: center;
        margin-top: 2vw;
        margin-right: 3vw;
        display: none;

    }

    .page3-circle2 svg {
        height: 30%;
        rotate: -45deg;
    }

    .circle-in {
        height: 100%;
        width: 100%;
        position: absolute;
        top: 0;
        left: 0;
        background-color: #fff;
        display: -webkit-box;
        display: -ms-flexbox;
        display: flex;
        -webkit-box-align: center;
            -ms-flex-align: center;
                align-items: center;
        -webkit-box-pack: center;
            -ms-flex-pack: center;
                justify-content: center;
        /* display: ; */
        -webkit-transition: all ease 0.5s;
        -o-transition: all ease 0.5s;
        transition: all ease 0.5s;
        scale: 0;
        border-radius: 50%;
    }

    .circle-in p {
        font-size: 0.95vw;
        color: #000;
        font-weight: 500;
        width: 60%;
        scale: 0;
        -webkit-transition: all ease 0.5s;
        -o-transition: all ease 0.5s;
        transition: all ease 0.5s;
        -webkit-transition-delay: 0.3s;
             -o-transition-delay: 0.3s;
                transition-delay: 0.3s;
        opacity: 0;
    }

    .page3-circle1:hover .circle-in {
        scale: 1;
    }

    .page3-circle1:hover p {
        scale: 1;
        opacity: 1;
    }

    .page3-circle2:hover .circle-in {
        scale: 1;
    }

    .page3-circle2:hover p {
        scale: 1;
        opacity: 1;
    }

    #page4 {
        min-height: 100vh;
        position: relative;
        width: 100%;
        /* background-color: rgb(61, 61, 61); */
        padding: 10vh 5vw;
    }

    #page4-content {
        width: 90vw;
        position: relative;
        margin-left: 0%;
        /* background-color: red; */
    }

    #page4-content h1 {
        font-size: 9.5vw;
        text-transform: uppercase;
        position: relative;
    }

    #page4-content h1::before {
        content: "03";
        position: absolute;
        font-size: 3vw;
        font-weight: 100;
        font-family: "silk serif";
        left: -12%;
        top: 8%;
    }

    #page4-content .underline {
        height: 1px;
        width: 100%;
        background-color: #fff;
        margin: 9vw 0 14vw 0;
    }

    #page4-content > p {
        font-size: 5.8vw;
        width: 90%;
        margin-bottom: 3vw;
    }

    #page4-flex {
        display: -webkit-box;
        display: -ms-flexbox;
        display: flex;
        -webkit-box-orient: vertical;
        -webkit-box-direction: normal;
            -ms-flex-direction: column;
                flex-direction: column;
    }

    #page4-flex img {
        width: 100%;
        margin: 5vw 0 8vw 0;
    }

    #page4-flex p {
        font-size: 4vw;
        width: 90%;
        margin-left: 0vw;
        margin-bottom: 5vw;
    }

    #page4-blue-div {
        background-color: #3F7DF4;
        width: 90vw;
        padding: 5vw;
        padding-bottom: 15vw;
        position: relative;
        margin-top: 0vh;
        margin-left: 0vw;
    }

    .blue-div-elem {
        display: -webkit-box;
        display: -ms-flexbox;
        display: flex;
        -webkit-box-align: start;
            -ms-flex-align: start;
                align-items: flex-start;
        -webkit-box-pack: justify;
            -ms-flex-pack: justify;
                justify-content: space-between;
        /* background-color: red; */
        padding: 4.7vw 0;
        border-bottom: 2px solid #ffffff94;
    }

    .blue-div-elem h4 {
        font-size: 3.9vw;
        font-weight: 500;
    }

    .blue-div-elem p {
        width: 50%;
        font-size: 3.6vw;
    }

    #page4-content .underline:nth-last-child(1) {
        margin: 26vw 0 7vw 0;
    }

    #page5 {
        min-height: 60vh;
        width: 100%;
        position: relative;
    }

    .elem {
        white-space: nowrap;
        overflow-x: hidden;
        margin-bottom: -2vw;
    }

    .elem h1 {
        font-size: 12vw;
        -webkit-text-stroke: 1px #fff;
        font-weight: 400;
        text-transform: uppercase;
        /* background-color: red; */
        color: transparent;
        display: inline-block;
        margin-right: 16px;
        -webkit-animation-name: anime;
                animation-name: anime;
        -webkit-animation-duration: 20s;
                animation-duration: 20s;
        -webkit-animation-timing-function: linear;
                animation-timing-function: linear;
        -webkit-animation-iteration-count: infinite;
                animation-iteration-count: infinite;
    }

    @-webkit-keyframes anime {
        from {
            -webkit-transform: translateX(0);
                    transform: translateX(0);
        }

        to {
            -webkit-transform: translateX(calc(-100% - 20px));
                    transform: translateX(calc(-100% - 20px));
        }
    }

    @keyframes anime {
        from {
            -webkit-transform: translateX(0);
                    transform: translateX(0);
        }

        to {
            -webkit-transform: translateX(calc(-100% - 20px));
                    transform: translateX(calc(-100% - 20px));
        }
    }


    .elem2 {
        white-space: nowrap;
        overflow-x: hidden;
        margin-bottom: -2vw;
    }

    .elem2 h1 {
        font-size: 12vw;
        -webkit-text-stroke: 1px #fff;
        font-weight: 400;
        text-transform: uppercase;
        /* background-color: red; */
        color: transparent;
        display: inline-block;
        -webkit-transform: translateX(calc(-100% - 20px));
            -ms-transform: translateX(calc(-100% - 20px));
                transform: translateX(calc(-100% - 20px));
        -webkit-animation-name: anime;
                animation-name: anime;
        -webkit-animation-duration: 25s;
                animation-duration: 25s;
        -webkit-animation-timing-function: linear;
                animation-timing-function: linear;
        -webkit-animation-iteration-count: infinite;
                animation-iteration-count: infinite;
        animation-direction: reverse;
    }

    .elem span {
        font-style: italic;
        font-family: "silk serif";
        color: transparent;
    }

    .elem2 span {
        font-style: italic;
        font-family: "silk serif";
        color: transparent;
    }

    #footer {
        height: 108vh;
        width: 100%;
        /* background-color: red; */
        margin-top: 20vw;
        position: relative;
        padding: 5vw 5vw;
        padding-bottom: 5vw;
    }

    #footer h1 {
        font-size: 9.7vw;
        text-transform: uppercase;
        /* background-color: blue; */
        position: relative;
    }

    #footer h1::before {
        content: "04";
        position: absolute;
        font-size: 5vw;
        font-weight: 100;
        font-family: "silk serif";
        left: 0%;
        top: -70%;
    }

    #footer-text {
        position: relative;
        /* background-color: red; */
    }

    #footer-text h2 {
        font-size: 9.7vw;
        position: absolute;
        top: -10%;
        font-weight: 500;
        opacity: 0;
        left: 0;
        font-family: "silk serif";
    }

    #footer-text h2 span {
        font-family: "silk serif";
        opacity: 0;
        -webkit-text-stroke: 1px #fff;
        color: transparent;
    }


    .underline {
        height: 1px;
        width: 100%;
        background-color: #fff;
        margin: 8vw 0;
    }

    #footer-div {
        display: -webkit-box;
        display: -ms-flexbox;
        display: flex;
        -webkit-box-align: start;
            -ms-flex-align: start;
                align-items: flex-start;
        -webkit-box-pack: justify;
            -ms-flex-pack: justify;
                justify-content: space-between;
        -webkit-box-orient: vertical;
        -webkit-box-direction: normal;
            -ms-flex-direction: column;
                flex-direction: column;
        padding-right: 15vw;
        padding-top: 4vw;
        margin-bottom: 6vw;
    }

    #footer-div h6 {
        font-size: 4.9vw;
        margin-bottom: 3.5vw;
        font-weight: 500;
    }

    .box {
        width: 30%;
        margin-bottom: 5vw;
    }

    #footer-div h5 {
        font-size: 5.4vw;
        margin-bottom: 1.5vw;
        font-weight: 500;
        /* margin: 0.1vh 0; */
    }

    #footer > h5 {
        font-weight: 500;
        margin-bottom: 4vw;
        font-size: 4vw;
    }
    #footer a{
        text-decoration: none;
    }
}
```



### JavaScript (script.js)

```Js
function locomotiveAnimation() {
  gsap.registerPlugin(ScrollTrigger);

  const locoScroll = new LocomotiveScroll({
    el: document.querySelector("#main"),
    smooth: true,
  
    // for tablet smooth
    tablet: { smooth: true },
  
    // for mobile
    smartphone: { smooth: true }
  });
  locoScroll.on("scroll", ScrollTrigger.update);
  
  ScrollTrigger.scrollerProxy("#main", {
    scrollTop(value) {
      return arguments.length
        ? locoScroll.scrollTo(value, 0, 0)
        : locoScroll.scroll.instance.scroll.y;
    },
    getBoundingClientRect() {
      return {
        top: 0,
        left: 0,
        width: window.innerWidth,
        height: window.innerHeight
      };
    }
  });
}
function loadingAnimation() {
  var tl = gsap.timeline();
  tl.from(".line h1", {
    y: 150,
    stagger: 0.25,
    duration: 0.6,
    delay: 0.5,
  });
  tl.from("#line1-part1", {
    opacity: 0,
    onStart: function () {
      var h5timer = document.querySelector("#line1-part1 h5");
      var grow = 0;
      setInterval(function () {
        if (grow < 100) {
          h5timer.innerHTML = grow++;
        } else {
          h5timer.innerHTML = grow;
        }
      }, 27);
    },
  });
  tl.to(".line h2", {
    animationName: "loaderAnime",
    opacity: 1,
  });
  tl.to("#loader", {
    opacity: 0,
    duration: 0.2,
    delay: 2.6,
  });
  tl.from("#page1", {
    delay: 0.1,
    y: 1600,
    duration: 0.5,
    ease: Power4,
  });
  tl.to("#loader", {
    display: "none",
  });
  tl.from("#nav", {
    opacity: 0,
  });
  tl.from("#hero1 h1,#hero2 h1,#hero3 h2,#hero4 h1", {
    y: 140,
    stagger: 0.2,
  });
  tl.from(
    "#hero1, #page2",
    {
      opacity: 0,
    },
    "-=1.2"
  );
}
function cursorAnimation() {
  Shery.mouseFollower({
    skew: true,
    ease: "cubic-bezier(0.23, 1, 0.320, 1)",
    duration: 1,
  });
  Shery.makeMagnet("#nav-part2 h4");

  var videoContainer = document.querySelector("#video-container");
  var video = document.querySelector("#video-container video")
  videoContainer.addEventListener("mouseenter", function () {
    videoContainer.addEventListener("mousemove", function (dets) {
      gsap.to(".mousefollower", {
        opacity: 0
      });
      gsap.to("#video-cursor", {
        left: dets.x - 570,
        y: dets.y - 300,
      });
    });
  });
  videoContainer.addEventListener("mouseleave", function () {
    gsap.to(".mousefollower", {
      opacity: 1

    });
    gsap.to("#video-cursor", {
      left: "70%",
      top: "-15%",
    });
  });



  var flag = 0
  videoContainer.addEventListener("click", function () {
    if (flag == 0) {
      video.play()
      video.style.opacity = 1
      document.querySelector("#video-cursor").innerHTML = `<i class="ri-pause-mini-fill"></i>`
      gsap.to("#video-cursor", {
        scale: 0.5
      })
      flag = 1
    } else {
      video.pause()
      video.style.opacity = 0
      document.querySelector("#video-cursor").innerHTML = `<i class="ri-play-mini-fill"></i>`
      gsap.to("#video-cursor", {
        scale: 1
      })
      flag = 0
    }
  })
}
function sheryAnimation() {
  Shery.imageEffect(".image-div", {
    style: 5,
    gooey: true,
    config:{"a":{"value":2,"range":[0,30]},"b":{"value":0.75,"range":[-1,1]},"zindex":{"value":-9996999,"range":[-9999999,9999999]},"aspect":{"value":0.7241195453907675},"gooey":{"value":true},"infiniteGooey":{"value":false},"growSize":{"value":4,"range":[1,15]},"durationOut":{"value":1,"range":[0.1,5]},"durationIn":{"value":1.5,"range":[0.1,5]},"displaceAmount":{"value":0.5},"masker":{"value":true},"maskVal":{"value":1.23,"range":[1,5]},"scrollType":{"value":0},"geoVertex":{"range":[1,64],"value":1},"noEffectGooey":{"value":true},"onMouse":{"value":0},"noise_speed":{"value":0.5,"range":[0,10]},"metaball":{"value":0.33,"range":[0,2]},"discard_threshold":{"value":0.5,"range":[0,1]},"antialias_threshold":{"value":0.01,"range":[0,0.1]},"noise_height":{"value":0.5,"range":[0,2]},"noise_scale":{"value":10,"range":[0,100]}}
  });
}
function flagAnimation() {

  document.addEventListener("mousemove", function (dets) {
    gsap.to("#flag", {
      x: dets.x,
      y: dets.y
    })
  })
  document.querySelector("#hero3").addEventListener("mouseenter", function () {
    gsap.to("#flag", {
      opacity: 1
    })
  })
  document.querySelector("#hero3").addEventListener("mouseleave", function () {
    gsap.to("#flag", {
      opacity: 0
    })
  })

}
function footerAnimation() {

  var clutter = ""
  var clutter2 = ""
  document.querySelector("#footer h1").textContent.split("").forEach(function (elem) {
    clutter += `<span>${elem}</span>`
  })
  document.querySelector("#footer h1").innerHTML = clutter
  document.querySelector("#footer h2").textContent.split("").forEach(function (elem) {
    clutter2 += `<span>${elem}</span>`
  })
  document.querySelector("#footer h2").innerHTML = clutter2


  document.querySelector("#footer-text").addEventListener("mouseenter", function () {
    gsap.to("#footer h1 span", {
      opacity: 0,
      stagger: 0.05
    })
    gsap.to("#footer h2 span", {
      delay: 0.35,
      opacity: 1,
      stagger: 0.1
    })
  })
  document.querySelector("#footer-text").addEventListener("mouseleave", function () {
    gsap.to("#footer h1 span", {
      opacity: 1,
      stagger: 0.1,
      delay: 0.35,

    })
    gsap.to("#footer h2 span", {
      opacity: 0,
      stagger: 0.05
    })
  })
}

loadingAnimation();
cursorAnimation();
locomotiveAnimation();
sheryAnimation();
flagAnimation()
footerAnimation()
```


Feel free to explore and customize the code to suit your preferences.

Made with ❤️ by [Ram](https://github.com/ramxcodes).
