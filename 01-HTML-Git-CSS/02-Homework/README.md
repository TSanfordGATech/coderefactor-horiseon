 make it more accessible. 
video captions, screen readers, and braille keyboards. 

make sure that all links are functioning correctly. 
ake it more efficient by consolidating CSS selectors and properties,
organizing them to follow the semantic structure of the HTML elements, 
and including comments before each element or section of the page.

Main bits from above: 
1. Clean it up
2. Ensure it is not dry code
3. Include the notes, what is it doing?
4. Ensure people with disabilities can access a website.
5. Create a solid read me file including what features you put in for accessibility
6. Make sure all of the links are functioning correctly 
7. Consolidate CSS selectors and properties
8. Include comments before each section or element.


## User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

## Acceptance Criteria

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title

---- broke this down to: 
Lets Map out the Acceptance Criteria: 
1.	We are given the site with accessibility standards. In this site we need to ensure ……
a.	When I look at the source code that it contains semantic HTML elements (Semantic HTML elements are those that clearly describe their meaning in a human- and machine-readable way. Elements such as <header> , <footer> and <article> are all considered semantic because they accurately describe the purpose of the element and the type of content that is inside them.)
b.	When I look at the HTML elements I find that they are placed in a logical structure, independent of the styling and positioning. This means, the CSS styling and positioning should be contained on a styles page. 
c.	When I view the image elements I find accessible alt attributes. This mean, each image has the Alt image telling them what it is. 
d.	When I view the heading attributes (HTML) they fall in sequential order. 
e.	When I view the title element, I find it is a concise and descriptive title. 

```

## Mock-Up

The following image shows the web application's appearance and functionality:

![code refactor demo](./Assets/01-html-css-git-homework-demo.png)


## Grading Requirements

This homework is graded based on the following criteria: 

### Technical Acceptance Criteria: 40%

* Satisfies all of the above acceptance criteria plus the following code improvements:

  * Application's links all function correctly.

  * Application's CSS selectors and properties are consolidated and organized to follow semantic structure.

  * Application's CSS file is properly commented.

### Deployment: 32%

* Application deployed at live URL.

* Application loads with no errors.

* Application GitHub URL submitted.

* GitHub repository that contains application code.

### Application Quality: 15%

* Application resembles (at least 90%) screenshots provided in the homework instructions.

### Repository Quality: 13%

* Repository has a unique name.

* Repository follows best practices for file structure and naming conventions.

* Repository follows best practices for class/id naming conventions, indentation, quality comments, etc.

* Repository contains multiple descriptive commit messages.

* Repository contains quality README file with description, screenshot, and link to deployed application.

## Review

You are required to submit the following for review:

* The URL of the deployed application.

* The URL of the GitHub repository. Give the repository a unique name and include a README describing the project.

- - -
© 2020 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.
