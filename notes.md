# cs260
notes for cs260 web programming

01/04/22
Tim Berners-Lee (web father): invented http, html, url browser 
<html>
<head></head>
<body><h1>message</h1>
css: styling the page directly within the browser
The Stack: database —> server technology —> web framer (makes complex user interface easy). 

01/06/22
- AWS vs Digital Ocean: functionality? cost? long term support? community activity? 
- Functionality 
  - AWS: Route53, security groups, stop instances, snapshot images hostname registrar
  - Digital Ocean: DNS, firewall, turn off (charges while on), snapshot

01/11/22
  - Vi Text Editor: I (insert), ctrl R redo, ctrl u undo, dd delete (command mode)
  - Head HTML: doesn't get displayed, tagged, metadata 
  - Body html: has headings, gets displayed, <p> paragraph, <a anchor links to another file 
  
 01/18/22
 - CSS: cascading style sheets, css uses selector to reach and apply specifications to certain members within HTML code 
 - *: base level selector, applies to everything | h1{color: red} only h1 | h1, h2{} does both| .className{} is class attribute | a:hover/a:visited {}              - CSS Box Model: boxes around boxes --> heart of the box is content (biggest part), then padding, the border, and the margin (Pals Before Marriage)
  
  01/25/22
  - assignment for tmrw: create a page w/ 0 functionaltiy (principles of good web design) to use with creative project 
  - creative project: create a website to plan out moving to costa rica? 
  - page title 96px, titles 48-20px, text 16px, secondary text 14px, input 16px <-- ideal font sizes 
  - color themes: if it occurs in nature you're good, pull from material theme builder 
  - iconography: use standard icons   
  - images must add value to the site                                                 
  - use whitespace conscientiously 
  - goal is to not make the user think too much   
  - search engine optimization: google search console, key to google crawling ur page is Robots.txt (within root of website, contains instructions for web crawling)
  
  02/03/22 --> JavaScript 
  - pair programming !== division of labour, instead define small tasks, driver (tactical)/ navigator(strategy)
  - loose equality does type conversion and unobvious equality rules  ( 1 == '1', 1 != '2', null == undefined)
  - strict equality doesn't do type conversions, uses falsy (keep going til you find something true or return false) ( 1 != '1', null != undefined)
  - logical nullish ??== operator, asisgned only when x is nullish (null/undefined)         

                                                                                    
  02/15/22 
  - midterm prep: midterm practice exam, review on thursday 
  - debugging javascript 
  1. let the language help - 'use strict', eslint                                                                                  
  2. resolve all warnings and errors                                                                                  
  3. define deliverable --> what is the expectation of what the code is 'supposed' to do? what's the big picture?
  4. review code and services 
  5. walk through the code in the debugger                                                                                   
  6. test all paths                                                                                   
  7. handle all error cases 
  8. use test driven development (TDD)  --> write documentation, write tests, and THEN develop                                                                         - if you write your code with performance in mind you will get it wrong
  1. optimize for real usage (cache, bandwidth, cpu, storage)
  2. optimize based on data (don't guess!)
  3. prioritize bottlenecks 
  4. look at download size
  5. compress, reduce, minify 
  6. lazy load
  7. use psychology 
  
  03/01/22
  - vue
  - for loops can iterate arrays and objects as well as generate numbers 
  - modularity is a core component of programming, allows for more manageable code that's easier to repeat with less bugs 
  - template must have one parent element with as much complexity as u want 
  - components can define content children as represented by template slots, there's always a default slot 
  
  03/03/22
  - Vue Single File Component: template, script, style 
  - tool for using vue: node.js
03/08/22
  - single page application: views, router(state contains current route component), vue component 
  - every vue component has properties (props) associated with each class 
  -  router dynamically loads the current component, computes what's to be dynamically displayed, istens for browser history to change the route, and can render dynamically calculated components 
03/29/22
  - ssh command server deployment (.sh file, git action)
  - put the front-end into public folder, allows so the private stuff stays protected 
  
