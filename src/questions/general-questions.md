---
title: General Questions
layout: layouts/page.njk
permalink: /questions/general-questions/index.html
---

* What did you learn yesterday/this week?
  * Reviewing data structures/algos specifically trees and graphs
  * Python
  * Recoil?
* What excites or interests you about coding?
  * I enjoy problem solving
  * exploring new technologies
  * always something new to learn (lifelong learning)
  * I enjoy that it is a skill than can be improved and not just a job
* What is a recent technical challenge you experienced and how did you solve it?
  * S : using that react-grid-layout library?
  * T :
  * A :
  * R : 
* When building a new web site or maintaining one, can you explain some techniques you have used to increase performance?
  * Planning and keeping the full scope of the project in mind
  * Having good commit messages on git hub
  * writing lists of things to do on the project/features to implement rather than going in blindly (tailor commit messages to this) - Notion
* Can you describe some SEO best practices or techniques you have used lately?
  * Using semantic HTML elements
  * Internal linking (from one page on your site to another on your site)
  * Title tag and meta description
* Can you explain any common techniques or recent issues solved in regards to front-end security?
  * API keys
  * Cross-Site Scripting - Injecting malicious scripts - can prevent by sanitizing all inputs (regex?)
  * DDoS attacks - reject overly high and suspicious traffic via firewalls/router
  * Cross-site Request Forgery
  * CSS injection - unauthorized access using CSS selectors
  * Security concerns in 3rd party libraries - dont use an excessive amount of libraries that you are unfamiliar with
* What actions have you personally taken on recent projects to increase maintainability of your code?
  * Version control with git, good commit comments
  * Created dev, staging, and production environments
  * Keeping syntax rules consistent, CSS in js vs CSS (linting?)
  * writing tests
  * Intuitive file structure
  * descriptive/accurate file names
  * Separation of concerns
* Talk about your preferred development environment.
  * VS Code + github
  * debugger
  * development vs staging vs production builds
  * powershell/node
* Which version control systems are you familiar with?
  * Git
* Can you describe your workflow when you create a web page?
  * Plan out design/functionaility > Plan technologies to use > file structure > how to separate components
* If you have 5 different stylesheets, how would you best integrate them into the site?
  * Make sure no overlapping rules between the stylesheets, add comments, only import the stylesheets into components that need them
* Can you describe the difference between progressive enhancement and graceful degradation?
* How would you optimize a website's assets/resources?
* How many resources will a browser download from a given domain at a time?
  * What are the exceptions?
* Name 3 ways to decrease page load (perceived or actual load time).
  * load JS asynchronously
  * Minify resources (webpack)
  * optimize images for smaller memory usage or lazy load
* If you jumped on a project and they used tabs and you used spaces, what would you do?
  * I would use tabs to create consistency in the project, it's a small sacrifice to make
* Describe how you would create a simple slideshow page.
* If you could master one technology this year, what would it be?
  * React/Javascript
* Explain the importance of standards and standards bodies.
  * Standards describe how technologies should be used, good to follow best practices
    * 'Open' standard - web should be free to contribute to and use, anyone can build website for free, HTML created by many different companies rather than owned by a single entity that could make it not free
  * Standards bodies are ECMA, W3C
* What is Flash of Unstyled Content? How do you avoid FOUC?
  * HTML rendering before CSS is applied
  * Solution: hide everything in body until page is done rendering, then return visibility
* Explain what ARIA and screenreaders are, and how to make a website accessible.
  * Accessible Rich Internet Applications
  * Make web content accessible for those with disabilities using assistive technologies (AT) like screen readers. Using semantic tags has similar affect to using role
    ```
    <ul role="navigation" aria-expanded="false" aria-labeledby="div1"></ul>
    ```
* Explain some of the pros and cons for CSS animations versus JavaScript animations.
  * use CSS for smaller self-contained states for UI elements, declarative, need minimum control (i used CSS for menu animation on portfolio and my loading screen)
  * use JS if you need more control (i used JS for pomocustom timeline)
* What does CORS stand for and what issue does it address?
  * Cross-Origin Resource Sharing
  * allows server to indicate origins that it permits loading resources, by default cant load resources from other domains unless the response from other origins includes the right CORS headers
* How did you handle a disagreement with your boss or your collaborator?
  * Try to see things from the other persons perspective, dont get defensive or too attached to certain ways of doing things.
  * S :
  * T :
  * A :
  * R : 
* What resources do you use to learn about the latest in front end development and design?
  * Youtube channels, 
  * Udemy courses, 
  * Podcasts (front-end happy hour), 
  * Newsletters (JS, HTML, CSS, Node)
  * MDN docs
* What skills are needed to be a good front-end developer?
  * Flexibility
  * Problem solving
  * a bit of design knowledge
  * knowledge of backend to know full context of application
* What role do you see yourself?
  * Front-end developer or Full-stack developer