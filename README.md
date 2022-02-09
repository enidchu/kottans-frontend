# kottans-frontend

## Stage 0. Self-Study

### General

### 0. [Git Basics](tasks/git-intro.md) <br>
My impressons of learning Git:

First of all, I would like to appreciate [learngitbranching](https://learngitbranching.js.org/) this website. It's very easy-using and including comprehensive knowledge of Git.

For the process of learning Git, the Rebase part confused me the most. 
Besides practicing the test developed by the website, I also searched informaion online got to know more clear about this concept.

Another thing is it took me more time to learn this tool as I estimated. 
I thought I could complete all the levels within 2 days, it turned out took me about 3 days to finish them.

Action is better than words, so I tried my 1st pull-request to get more familiar with this tool!

![alt text](https://github.com/enidchu/kottans-frontend/blob/main/task_git_basics/1st%20pull%20request.jpg?raw=true)
![alt text](https://github.com/enidchu/kottans-frontend/blob/main/task_git_basics/git%20completed.jpg?raw=true)

###  1. [Linux CLI and Networking](tasks/linux-cli-http.md)
My impression of learning Linux CLI and Networking:

I would like to appreciate [Linux Survival](https://linuxsurvival.com/linux-man-command-exercise/) first. It makes the knowleadge of Linux super easy-understanding! The way it explains about every Linux command is very clear. It also comes very practical quiz when each topic ends. 
I recommend this tutorial from bottom of my heart, it's very friendly for people who want to learn Linux even you don't have idea what it is!  
<br>![alt text](https://github.com/enidchu/kottans-frontend/blob/main/task_linux_cli/Linux%20Survival%20completed.png?raw=true)
<br>
#### On the other hand, HTTP Networking is a quite abstract topic while learning. <br>
Followings articles are the materials that course want us to read :
1. [HTTP: The Protocol Every Web Developer Must Know - Part 1](https://code.tutsplus.com/tutorials/http-the-protocol-every-web-developer-must-know-part-1--net-31177)
2. [HTTP: The Protocol Every Web Developer Must Know - Part 2](https://code.tutsplus.com/tutorials/http-the-protocol-every-web-developer-must-know-part-2--net-31155) <br>

It left me in a messed world while understanding. I read the above articles over and over again, also researched the mandarin materails additionally. After reading lots of papers, I concluded:
#### The knowledge of HTTP is very extensive, and my tour of HTTP began is just begun. With the basic foundation of URL schemes, status codes and request/response headers. Then building up with the finer areas, such as connection handling, identification and authentication and caching. 
#### The familiarity of HTTP relies on experiences. The situations are case-by-case, people get more familiar with it when fixing the problems. 

### 2. [GitHub and Collaboration](tasks/git-collaboration.md)
Finally completed my Stage 0 courses after having Git collaboration class! This course guides you the overall concept and flow of using remote repositories to work with other developers. The lessons are very detailed-written, so it took me few days to finish and pracite the whole content. It also provides addtional materials for referrence, quite useful! Hope I can get better at Git the more I do it.
![alt text](https://github.com/enidchu/kottans-frontend/blob/main/task_git_collaboration/GitHub%20Collaboration%20compelted.png?raw=true)

### Front-End Basics

### 3. [Intro to HTML and CSS](https://github.com/kottans/frontend/blob/master/tasks/html-css-intro.md)
I've learn HTML & CSS by myself before taking this course. HTML and CSS are not very difiicult, but need lots of practice. The "Form Course" in CodeAcademy is quite useful and helping, this is a part I never learnt before. I think there are plenty of snytaxs need to remember in these 2 languages, and for some advanced design may I need to learn bootstrape as well. Ok. let's move onto the next level!
![alt text](https://github.com/enidchu/kottans-frontend/blob/main/task_html_css_intro/HTML%20&%20CSS%20Intro%20Completed.png?raw=true)
![alt text](https://github.com/enidchu/kottans-frontend/blob/main/task_html_css_intro/learn%20HTML%20completed.png?raw=true)
![alt text](https://github.com/enidchu/kottans-frontend/blob/main/task_html_css_intro/learn%20CSS%20completed.png?raw=true)

### 4. [Responsive Web Design](tasks/html-css-responsive.md)
One thing made me impresssive was the course teaching us how to remotely debug on our phone! The video demostrated the tools of iOS and Android indivisually. The method is very new to me~ (Although these features were developed long time ago lol)
#### This course also deliver me some important insights, e.g. we should set following elements'size in percentage and better set them in "max-width": `img`, `embed`, `object`, `video`. Percentage setting makes all elements like water, they can easily change their shapes when doing responsive. `button` min-height & min-width DO NOT less than 48px, and plan your design from small screen to large screen. (whichh means media query should set in `min-width`)
Another course is [Flexbox Froggy](http://flexboxfroggy.com/), Flexbox is a really convinient method. can change elements' style right away. I think people can save much time if get familiar with it. 
![alt text](https://github.com/enidchu/kottans-frontend/blob/main/task_responsive_web_design/Responsive%20Web%20Design%20Fundamentals%20completed.png?raw=true)
![alt text](https://github.com/enidchu/kottans-frontend/blob/main/task_responsive_web_design/Flexbox%20Froggy%20completed.png?raw=true)

 ### 5. [HTML & CSS Practice](tasks/html-css-popup.md)
 The main purpose of this lesson is practcting how to generate a web page from 0. I don't think it was difficult at first, but it turned out to be more complex while makeing it out. It took me about 1 week to just bring about the "picture" :scream:. First I would like to note down is  "structure of HTML" and "naming CSS class". When seeing a picture, we can understand what elements we neeed e.g. navbar, button, table etc. 
#### However, the point is how people write the structure of elements and match with the CSS class. Taking this practice for example: <br>
```
    <nav>
       <ul class="nav-list">
          <li class="nav-list-item"><a href="#!">Mail</a></li>
          <li class="nav-list-item"><a href="#!">Images</a></li>
          <li class="nav-list-item">
              <input type="checkbox" class="nav-input-apps visually-hidden" id="nav-apps">
              <label for="nav-apps" class="nav-list-item-apps">
                 <span class="nav-list-item-apps-icon"></span>
              </label>
          </li>
       </ul>   
     </nav>
                                        
```
Here is just a part of the code, and we can see there are layers of HTML covering each other to create a object, and every HTML element matches with CSS class, in order to style the objects. 
#### The poor structure of HTML will infect people setting the CSS class, once class is messy, it does interfere people to write style as well. So practicing to write a firm HTML structure is very important to me. <br>
Another thing is: there are lots of detailed skill in wrting CSS too, since there are so many elements in CSS. Not to mention each of them has their own indiviual properties. It also took me quite a lot of effort to name the classes. I want to make sure the names of classes are clear and easy to understnd when reading the code. 
#### It's a good idea to make a remark when the codes represent different featues. Like following example:
```
/* pop-up menu apps list */
.nav-list-apps{
    overflow: overlay;
    position: relative;
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    justify-content: center;
    width: 320px;
    max-width: 500px;
}

/* pop-up menu apps list item */
.nav-list-apps-item{
    position: relative;
    display: flex;
    flex-direction: column;
    align-items: center;
    width: 90px;
    height: 98px;
    margin-bottom: 10px;
    list-style-type: none;
    border: 1px solid transparent;
    border-radius: 2px;
    color: #ccc;
    cursor: pointer;
}
```
I got myself-doubted for many times while doing this homework :sweat_smile:, thanks god I finally compelted it!!! I almost cried and felt the sense of achievement when pushing the file onto Github :joy:
