# Design Web Pages with CSS
Documents Referenced:
- [What is CSS?](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/What_is_CSS)

# CSS

## Overview
- Cascading Style Sheets (CSS) is a language that focuses on how a website is styled and presented to users.
- CSS allows you to override the interal HTML style sheet to control exactly how each HTML element looks in the browser.

Basic Styling you can Change:
- color
- size
- layouts
- animiations

## CSS Syntax
- Rules control specifically how each element type are styled

General Features of the Syntax
- Selector: selects the HTML element being styled
- Curly Braces `{}`: contain the properties and values modifying a given element
- Declarations:
  - Property: a characteristic associated with an element (placed prior to the colon)
  - Value: controls the outcome of the property characteristic (comes after the colon)

```Syntax Example
h1 {
    color: red;
    font-size: 5em;
}
```
[CSS reference](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)

New CSS features are developed by a team of professionals, but are ultimately only useful if adapted accross one or more browsers.

## Inserting CSS
There are three (3) ways to insert CSS styling:
1. External CSS: styling is controlled with an external .css file, which must be linked in the html document.
2. Internal CSS: styling is controlled in the `<head>` of the html document. This is best if one html page has specific style requirements.
3. Inline CSS: styling is applied to the elment of an html page in the attributes, but this looses advantages associated with External/Internal styling so use sparingly.

If multiple style sheets reference the same element, the value from the **last** last read sheet will be used.

Style priorities:
1. Inline Style (highest priority)
2. External/Internal Style
3. Browser Default (lowest priority)

