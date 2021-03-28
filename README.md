# 01 HTML CSS Git: Code Refactor instructions

One of the most common tasks for front-end and junior developers is to take existing code and refactor it to either meet a certain set of standards or implement a new technology. Web accessibility is an increasingly important consideration for businesses, ensuring that people with disabilities or socio-economic restrictions have access to their website, and helping them avoid litigation.

Your task is to refactor an existing webpage to make it accessible. An important rule to follow when working with someone else's code is the Scout Rule:

> Always leave the code you are editing a little cleaner than you found it.

To impress clients, you should always go the extra mile and improve their codebase for long term sustainability. Ensure that all links are functioning correctly and clean up the CSS to make it more efficient, consolidating CSS selectors and properties, organizing them to follow the semantic structure of the HTML elements, and including comments before each element or section of the page.

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
```

## Review

You are required to submit the following for review:

* The URL of the deployed application.

* The URL of the GitHub repository. Give the repository a unique name and include a README describing the project.

- - -
© 2021 Trilogy Education Services, LLC, a 2U, Inc. brand. Confidential and Proprietary. All Rights Reserved.
# My notes on the project

This is the area where I will type out detailed notes on what I did for this
challenge.

## HTML Edits

1. The first thing I decided to do was look at the HTML and start from the title.
I saw that the title needed to be changed so I changed it from website to Horiseon Main page.

2. Next I looked at the div tag that is being used as a header. Decided to change that into a header tag to utilize more semantic html. I also saw another div tag being used for the nav bar and realized I could use the nav tag instead.

NOTE: I went section by section commenting where a section starts each time I move along

3. After the header I looked and saw we were using a div tag with the class hero to create a hero/jumbotron image for the site. Instead of a div tag I decided that a section tag is more semantic to use based on the module project that we did. In our module project we used a section tag for the hero rather than a div. The difference between the two instances is that the hero in the module assignment/practice had a form in it and the hero for this project does not. 

4. After that I went down and saw another div tag being used for the next section, on further investigation I saw a couple things that could be changed. For starters I saw that semantically we could change all of the div tags to make better sense. So I changed the <div class="content> to <section class="content"> and the divs within that into articles. This decision was based on experience from the module project. When we worked on the meet the trainer section I followed the instructions and created a section using the section tag and the individual bios for the trainers using the article tag. Following that example I did the same thing here for the content section. There was also one other thing that was causing issues as well. The div for Search Engine optimization didnt have an id that would allow the nav bar to navigate to it. So when I changed the tag for it from div to article I also added an Id to make sure the nav bar would work.

5. After the content section I went on to work on the benefits section. Looking at this section I saw that I had to change the tags again to follow semantic HTML. While doing this I was looking up some semantic HTML to see if I was following the rules (Used these websites: http://web-accessibility.carnegiemuseums.org/foundations/semantic/ ; https://www.w3schools.com/tags/tag_aside.asp), and came across something called an aside tag that is used for content that is like a sidebar to the main content of the page. While looking at the webpage and the final mock up, I felt it best to define the benefits section as an aside as a whole with 3 articles within it. So, barring checking with a TA (Which I plan to do if I can) I decided to stick with this semantic logic and change the <div class="benefits"> to <aside class="benefits">; and changed the divs within it to articles.

6. Finally we reached the footer, The issue with the code here is that like the header it uses a div with the class footer. Instead of doing that we could just change the div into a footer, like we did to the header.

NOTE: I plan to Consult the TA to check if I followed and understood the instruction for all of these exercises.

5(Revised). After looking at this article (https://aastudio.fr/Sidebar-and-Aside-are-different.html#:~:text=is%20an%20HTML5%20tag,side%20of%20the%20main%20content.) I felt that the aside tag doesnt really fit the use case I was using it for, yes its a sidebar article but it is not related or relating itself to an article or section it is supposed to be a part of. So instead I will treat this as another seperate section with articles.

NOTE: At this point I went and finished my first wave of edits on HTML, My second wave of edits to the HTML will come after I change or edit the css and need to alter the classes somewhat to match the tags


## CSS Edits
```

```
