# BloggieBlog
A newsfeed blog developed with HTML, CSS and JavaScript with frontend development skills, including various features of header, search bar, featured articles, posts, popular tags, newsletter and media queries, and so on.<br/><hr>
# Functionalities/Demo
[BloggieBlog Overview-1.PNG](https://github.com/KrystalZhang612/BloggieBlog/blob/main/BloggieBlog%20Overview-1.png)<br/>
[BloggieBlog Overview-2.PNG](https://github.com/KrystalZhang612/BloggieBlog/blob/main/BloggieBlog%20Overview-2.png)<br/> 
[BloggieBlog Overview-3.PNG](https://github.com/KrystalZhang612/BloggieBlog/blob/main/BloggieBlog%20Overview-3.png)<br/>
[BloggieBlog Overview-4.PNG](https://github.com/KrystalZhang612/BloggieBlog/blob/main/BloggieBlog%20Overview-4.png)<br/> 
[BloggieBlog Overview-5.PNG](https://github.com/KrystalZhang612/BloggieBlog/blob/main/BloggieBlog%20Overview-5.png)<br/> 
- A responsive blog website from scratch.
- A header section that holds the navigation and all of its items.
- A theme toggle button that transitions the color scheme into the light scheme.
- It uses JavaScript Store, so the theme selection remains active when closing the webpage. - A search button with a popping up activated search bar when clicking the button.
- Signin and Signup buttons with neon effect.
- A main section with a nested grid that is split into two sides with creative layouts.
- A right-hand-side sidebar contains a quick read section utilizing JavaScript library `Swiper`, which creates a responsive carousel, to achieve arrows in pagination work.
- Older Posts section and Popular Tags section that are composed of six cards.
- A Newsletter section prompting users to subscribe to the newsletter if they want to.
# Developing Tools
[JavaScript Swiper](https://swiperjs.com/)<br/>
[Vscode 1.72](https://code.visualstudio.com/updates/v1_72)<br/>
[Live Server Vscode Extension v5.7.9](https://www.vsixhub.com/vsix/1950/)<br/>
# Build 
[Prerequisites & Setup](https://github.com/KrystalZhang612/BloggieBlog/blob/main/README.md#prerequisites--setup)<br/>
[Method Running The Project(Locally)](https://github.com/KrystalZhang612/BloggieBlog/blob/main/README.md#method-running-the-projectlocally)<br/> 
[Debugging&Troubleshooting](https://github.com/KrystalZhang612/BloggieBlog/blob/main/README.md#debuggingtroubleshooting)<br/> 
[Synchronous Developing Notes]()<br/> 
[Testing Results]()<br/> 
# Contribution
[Author]()
# Compatibility
`Windows 10`, `WSL Vscode 1.68+`, `Linux Ubuntu 22.04.1 LT`, `MacBook OS Monterey 12.6+`
# Prerequisites & Setup
## ***Set up Header***
In [index.html](https://github.com/KrystalZhang612/BloggieBlog/blob/main/Starter/index.html) under [Starter](https://github.com/KrystalZhang612/BloggieBlog/tree/main/Starter):<br/>
Make Header contains a navigation bar contains a menu of lists and their list-items:<br/>
```JavaScript 
<!-- Header -->
    <header class = "header" id = "header">
        <nav class = "navbar container">
            <a href = "./index.html">
                <h2 class = "logo">BloggieBlog</h2>
            </a>
            <div class = "menu" id = "menu">
                <ul class = "list">
    current">Home</a>
<li class="list-item">
    <a href = "#"  class = "list-link
</li>
<li class="list-item">
                        <a href = "#"  class =
"list-link">Categories</a>
                    </li>
                    <li class="list-item">
                        <a href = "#"  class = "list-link">Reviews</a>
                    </li>
                    <li class="list-item">
                        <a href = "#"  class = "list-link">News</a>
                    </li>
                    <li class="list-item">
                        <a href = "#"  class =
"list-link">Membership</a>
                    </li>
                    <li class="list-item">
                        <a href = "#"  class = "list-link">Contact</a>
                    </li>
                    <li class="list-item">
                        <a href = "#"  class = "list-link">Sign in</a>
                    </li>
                    <li class="list-item">
                        <a href = "#"  class = "list-link">Sign up</a>
                    </li>
</ul> </div>
        </nav>
    </header>
```
Click `Go Live`, and the 8 list-items shows on `localhost` as:<br/>
[8 list-items.PNG](https://github.com/KrystalZhang612/BloggieBlog/blob/main/8%20list-items.png)<br/>
Adding a base button as sun and moon icons underneath the list items:
```JavaScript
 <div class = "list list-right">
   <button class = "btn place-items-center" id = "theme-toggle-btn">
   <i class="ri-sun-line sun-icon"> </i>
   <i class="ri-moon-line moon-icon"> </i>
</button>
```
[sun and moon icons.PNG](https://github.com/KrystalZhang612/BloggieBlog/blob/main/sun%20and%20moon%20icons.png)<br/>
Adding a search button and a closed-menu button:<br/>
```JavaScript 
  <button class = "btn place-items-center" id = "search-icon">
  <i class="ri-search-line"> </i>
  </button>
 <button class = "btn place-items-center screen-lg-hidden
menu-toggle-icon" id = "menu-toggle-icon">
 <i class="ri-menu-3-line open-menu-icon"> </i>
 <i class="ri-close-line close close-menu-icon"> </i>
 </button>
```
[search button and closed-menu button.PNG](https://github.com/KrystalZhang612/BloggieBlog/blob/main/search%20button%20and%20closed-menu%20button.png)<br/>
Hide specific signin and signup items into small screen:<br/>
```JavaScript 
 <a href = "#" class = "list-link screen-sm-hidden">Sign in</a>
  <a href = "#" class = "list-link screen-sm-hidden btn sign-up-btn
fancy-border">
   <span>Sign up</span></a>
```
# Method Running The Project(Locally)
Download the entire Starter folder of the BloggieBlog project to the local directory. <br/>
Open the project with Vscode on local device.<br/>
Install Vscode Extension [Live Server Vscode Extension v5.7.9](https://www.vsixhub.com/vsix/1950/)<br/>
Open [index.html](https://github.com/KrystalZhang612/BloggieBlog/blob/main/Starter/index.html) in Starter folder in Vscode. <br/>
Click `Go Live` on the bottom bar to view the BloggieBlog page. <br/>
# Debugging&Troubleshooting
-  Error: Menu item not showing when clicking the menu toggle icon. DEBUGGING: Change opacity from 0 to 1 to make the menu list display.
-  

# Synchronous Developing Notes
## ***Base - CSS:***
In [main.css](https://github.com/KrystalZhang612/BloggieBlog/blob/main/Starter/assets/css/main.css) under Starter:<br/> 
For the base styles:
```css
*{
margin: 0;
padding: 0;
    box-sizing: border-box;
}
html{
    /* font-size: 10px;*/
    font-size: 62.5%;
} body{
    font-family: var( --font-family);
    font-size: var(--font-size-sm);
    color: var(--light-color-alt);
    background-color: var(--primary-background-color);
    letter-spacing: 1px;
    transition: background-color .25s, color .25s;
}
a{
    text-decoration: none;
    color: inherit;
} img{
    max-width: 100%;
    display: block;
}
ul{
    list-style: none;
}
input,
button{
    font: inherit;
    color: inherit;
    border: none;
 
background-color: transparent;
    outline: none;
}
i{
    font-size: var(--font-size-md);
}
```
For the theme color:
```css
body.light-theme{
    --light-color: #3d3d3d;
    --light-color-alt: rgba(0,0,0,.6);
    --primary-background-color: #fff;
    --secondary-background-color: #f1f1f1;
    --hover-light-color: #fff;
    --transparent-light-color: #252830;
    --transparent-dark-color: rgba(0,0,0,.1);   }
```
For Reusable classes:
```css
.container{
    max-width: 160rem;
    margin: 0 auto;
    padding: 0 1.5rem;
}
.place-items-center{
    display: inline-flex;
    align-items: center;
    justify-content: center;
}
```
And set the items as hidden into a small screen at the end:
```css
.screen-sm-hidden{
    display: none; }
```
[after setting up CSS Base.PNG](https://github.com/KrystalZhang612/BloggieBlog/blob/main/after%20setting%20up%20CSS%20Base.png)<br/>
## ***Header - CSS:***
```css
.header{
    background-color: var(--secondary-background-color);
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    z-index: 999;
} .navbar{
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding-block: 1.5rem;
}
.logo{
    font-size: var(--font-size-md);
    color: var(--light-color);
} .menu{
    position: absolute;
    top: 8.5rem;
    right: 1.5rem;
    width: 23rem;
    padding: 1.5rem;
    background-color: var(--secondary-background-color);
    /*opacity: 0;
    transform: scale(0);*/
    transition: opacity .25s ease-in;
}
.list{
    display: flex;
    align-items: center;
    gap: var(--gap);
}
.menu > .list{
    flex-direction: column;
}
.list-link.current{
    color: var(--light-color);
}
.close-menu-icon{
    display: none;
} .btn{
    cursor: pointer;
}
.list-link:hover,
.btn:hover,
.btn:hover span{
    color: var(--light-color);
}
.moon-icon{
    display: none;
}
.light-theme .sun-icon{
    display: none;
}
.light-theme .moon-icon{
    display: block; }
```
## ***Header JavaScript Styles:***
Have the header and the menu activated:
```css
.header.activated{
    box-shadow: 0 1px .5rem var( --transparent-light-color);}
.menu.activated{
    box-shadow: 1px 1px 1rem var( --transparent-light-color);
    opacity: 1;
    transform: scale(1); }
```
Switch the icons:<br/> 
When it’s activated, target it to the open menu icon:
```css
.menu-toggle-icon.activated .open-menu-icon{
    display: none; }
 .menu-toggle-icon.activated .close-menu-icon{
    display: block; }
```
## ***JavaScript Events Management:***
Go to [main.js](https://github.com/KrystalZhang612/BloggieBlog/blob/main/Starter/assets/js/main.js)<br/>
To Grab Element:<br/>
Select element, if sth goes wrong, throw an error and specify the selector:
```JavaScript 
 const selectElement = selector => {
    const element = document.querySelector(selector)
    if(element) return element;
    throw new Error('Something went wrong, make sure that ${selector}
exists or is typed correctly.'); }
```
Call it and pass the navigation bar to test if above function works:
```JavaScript 
 console.log(selectElement('.navbar'));
```
Navigate the styles on scroll:
```JavaScript 
 const scrollHeader = () => {
    const headerElement = selectElement('#header');
    if(this.scrollY >= 15){
        headerElement.classList.add('activated');
    } else{
        headerElement.classList.remove('activated');
    }
};
```
Make Scroll header visible by calling it in add event listener:
```JavaScript 
window.addEventListener('scroll', scrollHeader);
```
Test it by setting the transparent-light-color to red in [main.css](https://github.com/KrystalZhang612/BloggieBlog/blob/main/Starter/assets/css/main.css):
```css
.header.activated{
    box-shadow: 0 1px .5rem var( --transparent-light-color);
    background-color: red;
}
```
Also add Search division in [index.html](https://github.com/KrystalZhang612/BloggieBlog/blob/main/Starter/index.html):
```JavaScript 
<div class = "search"></div>
```
So when we scroll down the webpage, the navigation bar turns to red:<br/>
[nav bar turns into red.PNG](https://github.com/KrystalZhang612/BloggieBlog/blob/main/nav%20bar%20turns%20into%20red.png)<br/>
Open menu & search pop-up:<br/>
```JavaScript
const menuToggleIcon  = selectElement('#menu-toggle-icon');
const toggleMenu = () => {
    const mobileMenu = selectElement('#menu');
    mobileMenu.classList.toggle('activated');
    menuToggleIcon.classList.toggle('activated');
};
```
Then call the menu toggle icon with add event listener:
```JavaScript
menuToggleIcon.addEventListener('click', toggleMenu);
```

















# Testing Results
[8 list-items.PNG](https://github.com/KrystalZhang612/BloggieBlog/blob/main/8%20list-items.png)<br/>
[sun and moon icons.PNG](https://github.com/KrystalZhang612/BloggieBlog/blob/main/sun%20and%20moon%20icons.png)<br/>
[search button and closed-menu button.PNG](https://github.com/KrystalZhang612/BloggieBlog/blob/main/search%20button%20and%20closed-menu%20button.png)<br/>
[after setting up CSS Base.PNG](https://github.com/KrystalZhang612/BloggieBlog/blob/main/after%20setting%20up%20CSS%20Base.png)<br/>
[nav bar turns into red.PNG](https://github.com/KrystalZhang612/BloggieBlog/blob/main/nav%20bar%20turns%20into%20red.png)<br/>






















 
