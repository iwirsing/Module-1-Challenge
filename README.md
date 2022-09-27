# **Module 1 Challenge: Horiseon - Marketing Agency Website**
Refactoring an existing website to meet accessibility standards and improve accessibility. 
  
## <u>Deployed Page</u>

[Horiseon - Marketing Agency Website](https://iwirsing.github.io/Module-1-Challenge-Horiseon/)

## <u>User Story</u>

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

## <u>Acceptance Criteria</u>

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

## <u>Changes Made to Code</u>

### **Title:**
- Changed to a more descritive website title: Horiseon - Marketing Agency.

### Body:
- Set min width to 950px so the elements are not layed over on top of each other when the browser is reduced in size.

### Header: 
- Fixed missing id to make menu link work correctly.
- Added `:hover` and `background color` for the header menu for increased readability.
- Changed position of header to fixed for ease of navigation for the user.

### Section and Aside: 
- Changed div elements to semantic tags (header, nav, figure, section, article, aside, footer).
- Added descriptive alt text for images.
- In the section area, added scroll margin top so the fixed header no longer blocks the article being snapped to.
- Consolidated repetitive CSS for content articles and aside.
- Change class names to reflect more of what they do.
- Added comments in the html and css identify the role of each area to the website.
- Re-arranged css to match elements in html.



## <u>Screenshot</u>
![Screenshot of index.html](./assets/images/Horiseon-Webpage-Screenshot.png)

## <u>License</u>

MIT License
Copyright <2022> \<Ivy Wirsing>

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## <u>SOURCES</u>
1. [Use of Hover](https://www.w3schools.com/cssref/sel_hover.asp)
2. [Use of Min-Width](https://developer.mozilla.org/en-US/docs/Web/CSS/min-width#:~:text=The%20min%2Dwidth%20CSS%20property,value%20specified%20for%20min%2Dwidth%20.)





