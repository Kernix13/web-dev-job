# Front-End Developer Notes

I have so much information in this file that I am going to have to have different sections and formats that have a lot of repeated notes.

<div id="back-to-top"></div>

## Table of contents

1. [Front End Development](#front-end-development)
1. [Experience and Know-How](#experience-and-know-how)
1. [Web Development](#web-development)
   1. [Basics](#basics)
   1. [Command line and Git](#command-line-and-git)
   1. [Server and hosting](#server-and-hosting)
   1. [Advanced](#advanced)
1. [Useful links](#useful-links)
   1. [Article 1](#article-1)
   1. [Article 2](#article-2)
   1. [Article 3](#article-3)
   1. [Article 4](#article-4)
   1. [Article 5](#article-5)
   1. [Article 6](#article-6)
   1. [Article 7](#article-7)
   1. [Article 8](#article-8)
   1. [Other Links](#other-links)
1. [Other Notes](#other-notes)

## Front End Development

1. Who are you?
1. What do you like to do?
1. What is your favorite part of the process?
1. What are YOU going to bring to the team?
1. Are you especially interested in animations?
1. How did you work thru problems with your project(s)?
1. Do you have a passion for UX or forms or security?
1. What special skills and personality will you bring to the team?
1. What interesting problems do you want to solve?
1. Your thought process. Why should I hire you?

## Experience and Know-How

Foundational Front-End Developer:

1. Setup a productive development environments
2. HTML, CSS, JavaScript
3. Use SASS & CSS frameworks (these are optional)
4. Create responsive layouts maybe from PSD mockup
5. Build sites w\ some dynamic functionality & work w\ the DOM
6. Connect to 3rd party APIS w\ Fetch & understand basic HTTP |
7. Use Git w\ GitHub or some other Git repo |
8. Deploy & manage a website or small web app |

Next Step:

1. Sharpen your JS skills w\ advanced JS (algorithms)
2. Learn a frontend js framework like Vue, React, Angular
3. Learn a server-side language / technology like Node, Python, PHP

| Subject              | My Level     |
| :------------------- | :----------- |
| HTML                 | Intermediate |
| CSS                  | Intermediate |
| JavaScript           | Intermediate |
| jQuery               | Beginner     |
| Responsive design    | Intermediate |
| React                | Beginner     |
| Vue. Angular         | -            |
| Testing & debgging   | Beginner     |
| Web performance      | Intermediate |
| version control      | Intermediate |
| browser dev tools    | Intermediate |
| Terminal             | Intermediate |
| APIS                 | Beg/Inter    |
| Server-side css      | -            |
| Progressive web apps | -            |
| State management     | Beginner     |
| Node.js              | Beginner     |
| Parcel               | Intermediate |
| Webpack              | Beginner     |

- Contributing to open source is very important

<div align="right">&#8673; <a href="#back-to-top" title="Table of Contents">Back to Top</a></div>

## Web Development

Traversy video: Web Development In 2021 - A Practical Guide

### Basics

- Design Software for client mockups: Adobe XD, Photoshop, Sketch, Figma
- html5 page structure & semantic tags |
- CSS: positioning, alignment(flex, grid), transitions, animation, responsive design
- SASS: variables, functions, nesting, mixins – easy to learn
- CSS/UI Frameworks – they offer premade classes to create elements on the fly – Tailwind CSS, Bootstrap, Materialize, Bulma -
- UI Design: color, contrast, white space, scale (?), visual hierarchy, typography – have an eye for it – how much margin looks good, can you read the text, etc
- JavaScript!!!: 1. Basics – vars, arrays, Fx’s, loops, … 2. DOM & Styling – selecting & manipulating elements 3. Array Methods – foreach, map, filter, reduce, etc. 5. JSON – used 95% of the time w\ 3rd party APIs, 6. HTTP Requests – Fetch API – GET, POST, PUT, DELETE – the fetch API is built into the browser
- Browser developer tools: (console, network, storage, etc) ??? errors, - network tab shows the requests & responses that are made to & from servers, Application tab is used to work with local storage in the browser

<div align="right">&#8673; <a href="#back-to-top" title="Table of Contents">Back to Top</a></div>

### Command line and Git

- Terminal to use: Default, Hyper, PowerShell, Git Bash -
- Version Control – Git, Subversion
- Repo manager: GitHub, Bitbucket, GitLab
- Package bundler: NPM, Yarn
- Module bundler: Parcel, Webpack, Rollup – can hold off learning it
- Editor extensions & helpers: linting, prettier, live server, emmet, snippets,
- Git: continuous deployment by pushing to a repo

### Server and hosting

- How to make a good looking basic website live on the web or a frontend app deployment
- Static Hosting: Netlify, GitHub Pages, Heroku – NETLIFY is free and uses Git so just push to your repo
- cPanel hosting: InMotion, HostGator, BlueHost – cpanel includes a lot by default – use VPS and not Shared hosting
- FTP/SFTP: slow
- SSH: Secure Shell (Terminal)
- Have to know how to register and setup a domain name:
- Domain Names: Namecheap, Google Domains,
- Email Hosting: Namecheap, Zoho Mail, cPanel,
- SSL Certificates: Let’s Encrypt, Cloudflare, Namecheap – let’s encrypt is free
- Don’t deploy ANYTHING that isn’t HTTPS

<div align="right">&#8673; <a href="#back-to-top" title="Table of Contents">Back to Top</a></div>

### Advanced

- Front-end js frameworks enables you to build single page web apps, or SPAs, and the page loads w\ pre-built JS from the framework that is then inserted into a single page – they allows you to have intricate user interfaces which would be harder and take more time with vanilla JS – also good when working with a team – you can use any framework on the front end w\ any language on the server – Vue.js is a bit easier to learn than React -
- Each of these frameworks have their own eco-system and that’s State Management – the state of your applicatrion – it can get messy with global states w\o using a state manager – ???
- React state management: Context, Redux, MobX
- OPTIONAL: TypeScript – a superset of JS – brings a “strict” type system to JS – makes your code more robust & less prone to erros – Object Oriented Programming (classes, interfaces, generics, modules) – great for larger projects
- Testing: there are testing frameworks for diff languages
- Unit tests: units like Fx’s and classes
- Integration tests: modules tested as a group
- End-to-end tests: test workflow from start to finish
- Trending Front-End stuff – don’t focus on them as a beginner -
- 1st) Server Side Rendering (SSR Framework): next.js, nuxt.js, - big reason I SEO: when you build a single-page application with something like react, when you look at the sourcecode you won’t see much – so web crawlers don’t see the content – an SSR somehow prevents that
- 2nd) Static Site Generators – generate your pages at build-time as opposed to real-time, making them super fat and secure – Gatsby (React based), - you can still have a dynamic site and work with data → Gatsby: dynamic and uses GraphQL and can use a headless CMS
- 3rd) Headless CMS: like WordPress, Druple are backend only content mgmt system that is commonly used w\ static site generators, meaning you can create ontent w\o touching any code – a headless cms works in the same way but it doesn’t have that front-facing web page – it’s used strictly for the data part and you can add whatever you want for the front end – a popular option is to use Gatsy and connect it to a headless cms to get your content – he prefers Strapi – it’s an open-source node.js headless cms that you host yourself – WordPress is another option b\c it has a REST API built into it and Sanito.io is also great
- JAMSTACK: the last few technologies can fit into what is known as the jamstack – a web architecture w\ high performance, security & scalability at a low cost w\ a great dev experience – Jamstack stands for Javascript, APIs and Markup → static sites / assets, markdown, serverless, headless cms for content, hosting w\ services like Netlify and AWS
- I NEED – build apps w\ a front-end framework, work w\ component and global state, test code – optional are Typescript, server side rendering, Jamstack

<div align="right">&#8673; <a href="#back-to-top" title="Table of Contents">Back to Top</a></div>

## Useful links

The best articles I found on technical skills to get a Front-End Developer job.

### Article 1

[Key Differences Between Junior, Midlevel, Senior, and Lead Developers](https://distantjob.com/blog/junior-front-end-developer-skills/)

The top 6 technical skills to look for:

1. html, css, js - JavaScript is a logic-based programming language used to modify the content on a website and make it behave in different ways in response to a user’s actions. JavaScript helps developers build confirmation boxes, CTA’s, and add interactive features to a website
2. responsive design - self-explanatory
3. js frameworks -JavaScript frameworks are collections of JS code libraries that provide developers with pre-written code for programming tasks and features. This helps them save time. They don’t have to write the code from scratch or build certain features from zero – most popular are React, Angular, jQuery, and Vue
4. testing and debugging - Bugs are part of a development process, and they can mess things up when they are not detected - There are different testing methods in web development, such as functional testing that emphasizes a particular piece of functionality on your site, or unit testing that consists of testing the smallest bit of code that is making something fail in your site -
5. web performance - refers to the speed of a website - Sometimes this is done by minifying CSS and JavaScript; other times, it depends on the type of images you use. There are thousands of reasons why your website is slow, and talented front-end developers can fix these issues
6. version control - a category of software tools that help a developer change to source code over time - If your developer wants to get creative and make some innovative changes to the website, they can simulate it with VCS and see how it works - This is undoubtedly one of the most important tools for web development

<div align="right">&#8673; <a href="#back-to-top" title="Table of Contents">Back to Top</a></div>

### Article 2

[Top 10 Front End Developer Skills You Need to Know](https://www.edureka.co/blog/front-end-developer-skills)

Front end developer deals with what the user interacts with and back end is all that goes behind the scenes and makes it happen -A front end developer is someone who implements web designs through programming languages like HTML, CSS, and JavaScript. The front end developers work with the design and outlook of the website. Whereas, the back end developers program what goes on behind the scenes like databases

1. CSS and JavaScript frameworks are collections of CSS or JS files that perform different tasks by providing common functionality. Instead of starting with an empty text document, you start with a code file that has lots of JavaScript present already in it. Frameworks have their strengths and weaknesses which makes it important to choose the best framework for the type of website you’re building. For example, some JS frameworks are great for building complex user interfaces, while others excel at displaying all of your site’s content
2. html, responsive design, version control/git -
3. testing / debugging - must possess the skill and ability to test and debug codes. There are different testing methods for web development. Functional testing looks at a particular piece of functionality on your site and ensures it does everything according to the code - Unit testing is another method that tests the smallest bit of code and examines it individually for correct operation. Testing is a big part of the front end development process and there are frameworks to help you. Programs like Mocha and Jasmine are designed to speed up and simplify your testing process
4. Browser Developer Tools - modern web browsers come equipped with developer tools for testing and debugging. These tools allow you to test the web pages in the browser itself and finds out how the page is interpreting the code - Browser developer tools usually consist of an inspector and a JavaScript console. The inspector allows you to see what the runtime HTML on your page looks like, what CSS is associated with each element on the page, and also allows you to edit your HTML and CSS and see the changes live as they happen. The JS console allows you to view any errors that occur as the browser tries to execute your JS code
5. web performance - defines the amount of time it takes for your site to load - there are steps you can take to improve performance times such as optimizing images and minifying CSS and JavaScript - Programs like Grunt and gulp can be used to automate image optimization, CSS and JS minifying, and other web performance chores
6. css preprocessing - CSS Preprocessor is an advanced version of CSS. This is used to enhance the primary class of CSS to create better versions of websites. It is not just a language to improve the styling elements, but it helps the developers to skip tasks like writing CSS selectors and color strings frequently - There are three types of preprocessors available such as Sass, LESS and Stylus
7. command line - Although the majority of your work is done through a GUI, you can add serious cred to your front end skills if you have a mastery of the command line

<div align="right">&#8673; <a href="#back-to-top" title="Table of Contents">Back to Top</a></div>

### Article 3

[Front-End Developer Skills](https://www.thinkful.com/blog/front-end-developer-skills/)

Anything that the user can see or interact with is handled by the front-end developer. They focus on site design, layout, navigation, structure, fonts, colors, images, and content.

1. HTML: The properties of each element are defined by the HTML code you write. You'll need to understand the code if you want to fine-tune pages or fix errors
2. CSS: HTML dictates what to display, and CSS dictates how to display it - CSS is a powerful tool to create consistent themes on your site
3. JavaScript – HTML & CSS are extremely limited when it comes to developing more advanced user interfaces. JavaScript is needed for websites that incorporate interactive elements and features - animation elements, audio, video, games(https://codepen.io/alexlead/pen/dyMebea, )
4. Version Control (GIT) - helps developers track and control changes that have been made to the code -
5. Web Performance Optimization (WPO) - is the process of increasing the speed of a website - Faster downloads can improve visitor retention rates and ultimately provide a better user experience. This is especially true on mobile devices or when the user has a slow internet connection. Programs like Grunt and Gulp provide automated image optimization, tweak your CSS and JavaScript code, and perform many other web performance optimization tasks
6. graphic design - Displaying unique and bold graphics can help you achieve this. Figma, Photoshop, InVision, and Sketch are common design packages used by front-end developers
7. responsive design - allow the layout and design of a site to change depending on the type of device accessing it
8. Testing and Debugging - are extremely important for delivering a positive user experience - know how to check for JavaScript errors and debug code. You should learn how to perform effective cross-browser compatibility testing
9. Search Engine Optimization (SEO) - is the process of making sure a site is accessible by search bots and optimizing its ranking in search results - as a front-end developer, it doesn’t hurt to learn the basics. You’ll be mostly concerned with on-page SEO. This includes various design features you can build into sites to help them get discovered by Google and Yahoo. Internal linking structures, breadcrumb navigation, and the use of friendly URLs are all examples of on-page SEO concepts

<div align="right">&#8673; <a href="#back-to-top" title="Table of Contents">Back to Top</a></div>

### Article 4

[How to Become a Front End Developer - Skills, Roles, Salary Explained
](https://www.simplilearn.com/how-to-become-a-front-end-developer-article)

1. Have a degree in Computer Science or similar field
2. Be proficient in coding languages such as HTML, CSS, JavaScript, and jQuery
3. Understand server-side CSS.
4. Be experienced with graphic design applications (e.g., Adobe Illustrator)
5. Understand the principles of SEO
6. get informed - reading articles and books about front end development |
7. learn the command line |
8. version control |

<div align="right">&#8673; <a href="#back-to-top" title="Table of Contents">Back to Top</a></div>

### Article 5

[How Long It Takes to Become a Front End Developer](https://techbootcamps.utexas.edu/blog/how-long-it-takes-to-become-a-front-end-developer/)

1. Knowing and understanding the key principles of design
2. Understanding and using technologies like HTML, CSS, JavaScript, and jQuery
3. Using server-side CSS to enhance the user’s experience ???
4. Creating responsive, adaptive designs that work on desktop and mobile devices
5. Writing code that is reusable and understandable by others
6. Optimizing sites for speed and growth
7. Using design software like Adobe Illustrator and Adobe Photoshop

<div align="right">&#8673; <a href="#back-to-top" title="Table of Contents">Back to Top</a></div>

### Article 6

Dead link

1. frameworks: react, vue
2. Static Site Generators: next, nuxt, gatsby
3. JAMstack: Entire project served on a CDN | Everything lives in Git | Automated builds | Atomic deploys | Instant cache invalidation
4. Progressive web apps (PWA):
5. GraphQL:
6. Code Editors/IDEs: best extensions: JavaScript (ES6) code snippets, npm, Prettier, CSS Peek, Vetur, ESLint, Live Sass Compiler, Debugger for Chrome, Live Server, Beautify
7. testing:
8. clean code:
9. git
10. soft skills

<div align="right">&#8673; <a href="#back-to-top" title="Table of Contents">Back to Top</a></div>

### Article 7

[What is a front end developer](https://www.waveapps.com/freelancing/web-development/what-is-front-end-developer)

1. html
2. css
3. js
4. php
5. python
6. apis
7. building whole websites, landing pages, ecommerce pages, ...

<div align="right">&#8673; <a href="#back-to-top" title="Table of Contents">Back to Top</a></div>

### Article 8

[How I Found a Junior Frontend Developer Job](https://dev.to/ulyavrubel/how-i-found-a-junior-frontend-developer-job-in-2-weeks-after-1-year-of-self-learning-1lbn)

I don't think these list items go with the article above:

- HTML and the various web APIs |
- CSS3, FlexBox, CSS Grid |
- ES2015+ JavaScript |
- Frameworks like React, Angular, Vue |
- State management frameworks like Redux, MobX or ngrx/platform |
- Node.js tooling with Webpack/Rollup/Parcel |
- IDEs and Editors like VSCode |
- Chrome / Firefox DevTools

### Other Links

- [Hiring Without Whiteboards](https://github.com/poteto/hiring-without-whiteboards)
- [Twitter: pattern recognition](https://twitter.com/LDLockhartJr/status/1561251161134473217?s=20&t=Sb2aRdbdmveSWt1-JVsBUw)

<div align="right">&#8673; <a href="#back-to-top" title="Table of Contents">Back to Top</a></div>

## Other Notes

HAMBURGER:

- https://codepen.io/Phatlines/pen/bGvYOrP?editors=1010
- https://levelup.gitconnected.com/how-easy-i-code-a-hamburger-menu-with-css-and-javascript-5537d5669aa |

IF / ELSE AND SWITCH | HTML, CSS e-commerce page |

For starters you should understand Array, Linked List, Stack and Queue. And they are just classes with certain methods and a way of storing data. Array in JavaScript is an example of a Array data structure. It's a class (type) with push and pop methods. So Array is a data structure and some code, that for example traverses that array to find a certain value would be an algorithm
white-boarding?

- Algorithms – help your logic & critical thinking skills → FizzBuzz, string reversals, array chunking, palindromes, anagrams, max character, etc |
- Data Structures are also important – organize & manage data to perform specific operations: array, linked list, queue, stack, tree, graph, hash table |
- Software Design Patterns – look int olater – singleton, facade, strategy, bridge, observer

Junior Front End Developer Skills: ALSO SEARCH FCC FORUM FOR `#career` and `job` and `Career advice` - & google `junior web developer portfolios` – then study examples of portfolios from people who just got a junior developer job (look at projects and layout)

<div align="right">&#8673; <a href="#back-to-top" title="Table of Contents">Back to Top</a></div>
