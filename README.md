## Horiseon HTML, CSS, and Git Code Refactor

# Description
Restructure source code for Horiseon. Goal is to improve website operation without altering its functionality. 

# User Story

```
AS a marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```


# Acceptance Criteria

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the icon and image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```

# Changes Made
* Changed document title from "website" to "Horiseon"
* Renamed div elements to more appropriate semantics in index.html (main, header, article nav, section, aside)
* Altered the div elements in css.style to correspond with elements in index.html (div ---> nav)
* DRY'd up the unnecessary repeats of code in css.style
* Added alt tags to images in index.html
* Fixed a bug where the button on "Search Engine Optimization" did not lead to corresponding article

# Website Screenshot and URL
![Horiseon Website](.\assets\images\showcase-screenshot.jpg)