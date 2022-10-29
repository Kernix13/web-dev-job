# Interviewing Notes

I'm onlt including questions from varios GitHub repositories.

## Table of Contents

1. [GitHub Repo Sample Questions](#gitHub-repo-sample-questions)
   1. [General Questions](#general-questions)
   1. [HTML Questions](#html-questions)
   1. [CSS Questions](#css-questions)
   1. [JS Questions](#js-uestions)
   1. [Accessibility Questions](#accessibility-questions)
      1. [General](#general)
      1. [Technical](#technical)
      1. [Design](#design)
      1. [Content](#content)
      1. [Testing Questions](#testing-questions)
      1. [Performance Questions](#performance-questions)
      1. [Network Questions](#network-questions)
      1. [Coding Questions](#coding-questions)
      1. [Fun Questions](#fun-questions)
1. [JavaScript Interview Questions](#javaScript-nterview-questions)
1. [HTML and CSS Interview Questions](#html-and-css-interview-questions)

## GitHub Repo Sample Questions

[Front-end Developer Interview Questions](https://github.com/h5bp/Front-end-Developer-Interview-Questions)

### General Questions

1. What did you learn yesterday/this week?
1. What excites or interests you about coding?
1. What is a recent technical challenge you experienced and how did you solve it?
1. When building a new web site or maintaining one, can you explain some techniques you have used to increase performance?
1. Can you describe some SEO best practices or techniques you have used lately?
1. Can you explain any common techniques or recent issues solved in regards to front-end security?
1. What actions have you personally taken on recent projects to increase maintainability of your code?
1. Talk about your preferred development environment.
1. Which version control systems are you familiar with?
1. Can you describe your workflow when you create a web page?
1. If you have 5 different stylesheets, how would you best integrate them into the site?
1. Can you describe the difference between progressive enhancement and graceful degradation?
1. How would you optimize a website's assets/resources?
1. How many resources will a browser download from a given domain at a time?
   1. What are the exceptions?
1. Name 3 ways to decrease page load (perceived or actual load time).
1. If you jumped on a project and they used tabs and you used spaces, what would you do?
1. Describe how you would create a simple slideshow page.
1. If you could master one technology this year, what would it be?
1. Explain the importance of standards and standards bodies.
1. What is Flash of Unstyled Content? How do you avoid FOUC?
1. Explain what ARIA and screenreaders are, and how to make a website accessible.
1. Explain some of the pros and cons for CSS animations versus JavaScript animations.
1. What does CORS stand for and what issue does it address?
1. How did you handle a disagreement with your boss or your collaborator?
1. What resources do you use to learn about the latest in front end development and design?
1. What skills are needed to be a good front-end developer?
1. What role do you see yourself in?
1. Explain the difference between cookies, session storage, and local storage?

### HTML Questions

1. What does a doctype do?
1. How do you serve a page with content in multiple languages?
1. What kind of things must you be wary of when designing or developing for multilingual sites?
1. What are data- attributes good for?
1. Consider HTML5 as an open web platform. What are the building blocks of HTML5?
1. Describe the difference between a cookie, sessionStorage and localStorage.
1. Describe the difference between `<script>`, `<script async>` and `<script defer>`.
1. Why is it generally a good idea to position CSS `<link>`s between `<head></head>` and JS `<script>`s just before `</body>`? Do you know any exceptions?
1. What is progressive rendering?
1. Why you would use a srcset attribute in an image tag? Explain the process the browser uses when evaluating the content of this attribute.
1. Have you used different HTML templating languages before?
1. What is the difference between canvas and svg?
1. What are empty elements in HTML?

### CSS Questions

1. What is CSS selector specificity and how does it work?
1. What's the difference between "resetting" and "normalizing" CSS? Which would you choose, and why?
1. Describe Floats and how they work.
1. Describe z-index and how stacking context is formed.
1. Describe BFC (Block Formatting Context) and how it works.
1. What are the various clearing techniques and which is appropriate for what context?
1. How would you approach fixing browser-specific styling issues?
1. How do you serve your pages for feature-constrained browsers?
   1. What techniques/processes do you use?
1. What are the different ways to visually hide content (and make it available only for screen readers)?
1. Have you ever used a grid system, and if so, what do you prefer?
1. Have you used or implemented media queries or mobile specific layouts/CSS?
1. Are you familiar with styling SVG?
1. Can you give an example of an @media property other than screen?
1. What are some of the "gotchas" for writing efficient CSS?
1. What are the advantages/disadvantages of using CSS preprocessors?
   1. Describe what you like and dislike about the CSS preprocessors you have used.
1. How would you implement a web design comp that uses non-standard fonts?
1. Explain how a browser determines what elements match a CSS selector.
1. Describe pseudo-elements and discuss what they are used for.
1. Explain your understanding of the box model and how you would tell the browser in CSS to render your layout in different box models.
1. What does \* { box-sizing: border-box; } do? What are its advantages?
1. What is the CSS display property and can you give a few examples of its use?
1. What's the difference between inline and inline-block?
1. What's the difference between the "nth-of-type()" and "nth-child()" selectors?
1. What's the difference between a relative, fixed, absolute and statically positioned element?
1. What existing CSS frameworks have you used locally, or in production? How would you change/improve them?
1. Have you used CSS Grid?
1. Can you explain the difference between coding a web site to be responsive versus using a mobile-first strategy?
1. Have you ever worked with retina graphics? If so, when and what techniques did you use?
1. Is there any reason you'd want to use translate() instead of absolute positioning, or vice-versa? And why?
1. How is clearfix css property useful?
1. Can you explain the difference between px, em and rem as they relate to font sizing?
1. Can you give an example of a pseudo class? Can you provide an example use case for a pseudo class?
1. What is the difference between a block level element and an inline element. Can you provide examples of each type of element?
1. What is the difference between CSS Grid and Flexbox? When would you use one over the other?

### JS Questions

1. Explain event delegation.
1. Explain how this works in JavaScript.
   1. Can you give an example of one of the ways that working with this has changed in ES6?
1. Explain how prototypal inheritance works.
1. What's the difference between a variable that is: null, undefined or undeclared?
   1. How would you go about checking for any of these states?
1. What is a closure, and how/why would you use one?
1. What language constructions do you use for iterating over object properties and array items?
1. Can you describe the main difference between the Array.forEach() loop and Array.map() methods and why you would pick one versus the other?
1. What's a typical use case for anonymous functions?
1. What's the difference between host objects and native objects?
1. Explain the difference between: function Person(){}, var person = Person(), and var person = new Person()?
1. Explain the differences on the usage of foo between function foo() {} and var foo = function() {}
1. Can you explain what Function.call and Function.apply do? What's the notable difference between the two?
1. Explain Function.prototype.bind.
1. What's the difference between feature detection, feature inference, and using the UA string?
1. Explain "hoisting".
1. Describe event bubbling.
1. Describe event capturing.
1. What's the difference between an "attribute" and a "property"?
1. What are the pros and cons of extending built-in JavaScript objects?
1. What is the difference between == and ===?
1. Explain the same-origin policy with regards to JavaScript.
1. Why is it called a Ternary operator, what does the word "Ternary" indicate?
1. What is strict mode? What are some of the advantages/disadvantages of using it?
1. What are some of the advantages/disadvantages of writing JavaScript code in a language that compiles to JavaScript?
1. What tools and techniques do you use debugging JavaScript code?
1. Explain the difference between mutable and immutable objects.
   1. What is an example of an immutable object in JavaScript?
   1. What are the pros and cons of immutability?
   1. How can you achieve immutability in your own code?
1. Explain the difference between synchronous and asynchronous functions.
1. What is event loop?
   1. What is the difference between call stack and task queue?
1. What are the differences between variables created using let, var or const?
1. What are the differences between ES6 class and ES5 function constructors?
1. Can you offer a use case for the new arrow => function syntax? How does this new syntax differ from other functions?
1. What advantage is there for using the arrow syntax for a method in a constructor?
1. What is the definition of a higher-order function?
1. Can you give an example for destructuring an object or an array?
1. Can you give an example of generating a string with ES6 Template Literals?
1. Can you give an example of a curry function and why this syntax offers an advantage?
1. What are the benefits of using spread syntax and how is it different from rest syntax?
1. How can you share code between files?
1. Why you might want to create static class members?
1. What is the difference between while and do-while loops in JavaScript?
1. What is a promise? Where and how would you use promise?
1. Discuss how you might use Object Oriented Programming principles when coding with JavaScript.

#### Coding questions

Make this work:

```js
duplicate([1, 2, 3, 4, 5]); // [1,2,3,4,5,1,2,3,4,5]
```

- Create a for loop that iterates up to `100` while outputting "fizz" at multiples of `3`, "buzz" at multiples of 5 and "fizzbuzz" at multiples of `3` and `5`
- What will be returned by each of these?

```js
console.log("hello" || "world");
console.log("foo" && "bar");
```

- Write an immediately invoked function expression (IIFE)

### Accessibility Questions

#### General

- Who benefits from accessibility?
- How would you define inclusive and/or universal design?
  - Can you provide an example? (does not need to be web/tech related)
- How has your approach to accessibility changed over time?
- Name some ways responsive/mobile first design can affect accessibility.
- What are some user experience (UX) concerns to be aware of when using iconography in user interfaces (UI)?
- What assistive technologies (ATs) are you familiar with (desktop and/or mobile)?
  - What do you feel is your skill level with these AT(s)?
- What are skip links?
  - What benefit(s) do they provide?
  - What are some of their limitations?
- What are some of the tools available to test the accessibility of a website or web application?
- What is WCAG?
  - What are the differences between A, AA, and AAA compliance?
- How can using plain language benefit the accessibility of a project?
- Describe instances where one might use a link or button.
- Describe ways to convey an element or component’s state that aren’t entirely reliant on visuals.
- How can carousels be problematic for users with disabilities?
- How would you convince your Manager to allocate funds for an accessibility audit?
- Describe a situation where a coworker may have been resistant to accessibility or inclusive design best practices.
  - What sort of strategies do you use in situations like these to help educate coworkers?
- If one is looking to take on a leadership role:
  - Describe the kind of culture around accessibility you would create and how you would go about creating it
  - When there is more accessibility work to be done than the team can handle, how do you prioritize?
  - If a client/stakeholder doesn’t want to pay for accessibility what would you do?

#### Technical

- What methods can you use to find an element’s accessible name?
- What is the accessibility tree?
- Why are rems or ems preferable to pixels for setting type size?
- Why is it important to allow the viewport to be resized, and/or zoomed?
- How is the title attribute exposed to assistive technologies?
  - What kind of elements can title attributes be used on?
  - What sort of information is appropriate for use with the title attribute?
- Provide an example of when you might need to add a description to an element.
  - How would you expose that description programmatically?
- What is a focus trap, or focus trapping?
  - Describe an instance of when you’d need focus trapping.
  - Describe an instance of when this would be an accessibility barrier.
- Describe a situation where the tabindex attribute would be useful.
  - Provide an example of when using the tabindex attribute can cause problems.
- What are landmark regions and how can they be useful?
- In what situations might you use a toggle button, vs a switch control, vs a checkbox?
- Describe methods to hide content:
  - From all users.
  - From only screen reader users.
  - From sighted users, but not screen reader users.
  - And why you might do so.
- Provide examples of common incorrect usage of ARIA attributes.
- Aside from screen readers, what other assistive technologies can be affected by use of ARIA? How?
- What is the difference between the following attributes: hidden, aria-hidden="true" and role="presentation" or role="none"?
- Describe instances where you might need to use aria-live.
  - What values (such as assertive or polite) might you give the attribute in different situations?
- How would you mark-up an icon font or SVG that was for decorative purposes?
- Is CSS pseudo content understood by screen readers?
- What is the purpose of the alt attribute for images?
  - Can you describe the effect of an empty alt, and/or the lack of the attribute, on an image?
  - In what instances might an empty alt or no alt be appropriate?
  - How might alternative text for an image vary, depending on the context the image is used in?
  - Since svgs don’t accept the alt attribute, how can one provide alternative text for these graphics?
  - Do you need to supply an image an alt attribute if used witin a figure with a figcaption?
- Describe the steps you take in reviewing or auditing a website or application for accessibility?
- Describe an instance where an automated test would not flag a blatant accessibility error?
- When should you use or recommend ARIA roles or attributes to solve an accessibility issue?
- Describe your process for figuring out if an accessibility bug is due to a developer, browser, or assistive technology error?
- What is the difference between legend, caption and label elements?
  - What are their similarities?
- Describe the purpose of heading and header elements, and how they are useful in websites and applications.
- Describe how you’d handle managing keyboard focus within a single page web app (SPA) when changing routes.
- Name an ARIA attribute that requires either a child/parent relationship or a pairing role.
- What is your understanding of “accessible name computation” and how it affects modifying the way screen readers announce certain content?
- What are some issues with modifying normal scrolling behavior? For example: infinite scrolling or scrolljacking.
- Some ARIA widgets are presently best supported on devices with physical keyboard, rather than mobile/touch interfaces. Are you aware of any widgets that would be described this way, and why?

#### Design

- Talk about the pros and cons of flat and skeuomorphic design trends in regards to accessibility.
- Explain the importance of color contrast in designing for inclusion.
- Besides :hover, name other states an actionable element (links, buttons, form controls, etc.) could have styles for, and why providing them is important?
- When might it be appropriate to remove the visual outline from a focused element?
- If a form or form field were to return an error message, where might you want those error messages to be located?
- How can utilizing animation in an interface affect the user experience?
- Explain how you could make an infographic accessible for screen reader users.
- Why is color alone insufficient to draw attention to actionable elements, or to convey state?
- What are some of the inclusive UX problems that need to be solved when content (static or actionable) is revealed on :hover, and how would you propose solving for them?

#### Content

- What are some things you can do to make an accessible presentation?
- Is it possible to make email accessible?
- How can you make a podcast accessible?
- How would you make sure that a Word document is accessible?
- How would you make sure that an Excel spreadsheet document is accessible?
- Why is it important to tag a PDF correctly?
- What goes into making an accessible eBook?
- Tell me some social media accessibility best practices.
  - Facebook
  - Instagram
  - Pinterest
  - Snapchat
  - TikTok
  - Twitter
  - YouTube
- How would you handle a situation where your organization accidentally disseminates an inaccessible document?
- What do you think should happen if an employee repeatedly ignores making their documents accessible after being trained?
- What steps would you undertake to create a sustainable culture of creating accessible documents?
- In your previous experiences, was there an opportunity to insert accessibility checks and content authoring best practices into existing workflows?

### Testing Questions

1. What are some advantages/disadvantages to testing your code?
1. What tools would you use to test your code's functionality?
1. What is the difference between a unit test and a functional/integration test?
1. What is the purpose of a code style linting tool?
1. What are some of the testing best practices?

### Performance Questions

1. What tools would you use to find a performance bug in your code?
1. What are some ways you may improve your website's scrolling performance?
1. Explain the difference between layout, painting and compositing.

### Network Questions

1. Traditionally, why has it been better to serve site assets from multiple domains?
1. Do your best to describe the process from the time you type in a website's URL to it finishing loading on your screen.
1. What are the differences between Long-Polling, Websockets and Server-Sent Events?
1. Explain the following request and response headers:
   1. Diff. between Expires, Date, Age and If-Modified-...
   1. Do Not Track
   1. Cache-Control
   1. Transfer-Encoding
   1. ETag
   1. X-Frame-Options
1. What are HTTP methods? List all HTTP methods that you know, and explain them.
1. What is domain pre-fetching and how does it help with performance?
1. What is a CDN and what is the benefit of using one?

### Coding Questions

Go to the page to see them

### Fun Questions

1. What's a cool project that you've recently worked on?
1. What are some things you like about the developer tools you use?
1. Who inspires you in the front-end community?
1. Do you have any pet projects? What kind?

## JavaScript Interview Questions

[JavaScript Interview Questions](https://github.com/sudheerj/javascript-interview-questions)

There are over 400 questions so go to the repo for the specifics.

## HTML and CSS Interview Questions

Same as above, too many to list...

[HTML5 Interview Questions](https://github.com/learning-zone/html-interview-questions)

[CSS Interview Questions](https://github.com/learning-zone/css-interview-questions)
