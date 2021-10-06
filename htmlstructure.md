# Structure Web Pages with HTML
Documents Referenced:
- [The Definitive Guide: How To Make Your First Wireframe](https://careerfoundry.com/en/blog/ux-design/how-to-create-your-first-wireframe/)
- [HTML basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics)
- [Semantics](https://developer.mozilla.org/en-US/docs/Glossary/Semantics)


## Wireframing
A wireframe is a basic layout or skeleton of a website or app. Building a solid wireframe at the begining of a new project demsonstrates a clear understanding of how a user will interface with a website or app before effort is placed into coding or asthetics.

Wireframes can be created with hand drawings or by using some software tools, but ultimately the approach in creating these is up to the user. Depending on the end application for task at hand, multiple wireframes and tools may be used to walk through and solidify the final design. Backend projects may have just a wireframe and the coding, where as projects with a lot of customer interface may go through multiple iderations of wireframes both sketched and designed in software, before finally coding.

Wireframe Tools:
- Pen and Paper
- Slide Shows (Google Slides, PowerPoint, etc)
- Flowmap Tools (Lucidcharts, Visio, etc)
- Specific Wireframing Tools (UXPin, InVision, Wireframe.cc, etc)

Steps to Making a Wireframe:
1. Research - understand audience and competition
2. Reference - condense information from step 1 into a cheatsheet
3. Flow Map - create a flow map of the exepected interfaces with the website
4. Draft and Sketch - outline wireframe focusign on how you will support user goals without getting caught in the details
5. Details and Testing - add details from top to bottom left to right focusing on usability conventions, simple instructional wording, trust building elements, and tooltips, then start user testing
6. Prototype - use wireframing software to create production level prototypes

Wireframes overall should be clear, confident, and simple.

## HTML Basics
HTML stands for HyperText Markup Language and is the code that provides the basic structure for a website. HTML specifically uses tag notation to "markup" the text to perform a variety of different functions.

### Elements
Tags are enclosed in angle brackets <> and consist of an opening and closing tag. The closing tag is diferentiated from the opening tag by having a forward slash placed after the first angle bracket </>. These tags surround the content, and altogether form the HTML element.

[HTML element reference](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)

![HTML element](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics/grumpy-cat-small.png)

Attributes are portions of an element that contain extra information, but you don't want to appear in the acutal content of the element.
- space between the element
- attribute name should be followed by an equal sign
- attribute value should be wrapped by quotation marks ""

Elements can be nested to mark-up the content in more than one way.
```nesting
<p>The <strong>nested</strong> is emphasised</p>
```
To properly nest the elements the first tag opened should be the last tag closed, the second tag opened should be the second to last tag closed, and so on.

Some elements such as `<img>` are considered empty elements because there is no content or a subsequent closing tag. These elements instead use attributes to further define it.

### HTML Document Structure
- `<!DOCTYPE html>`, the html document must start with this.
- `<html></html>`, aka root element, this wraps all of the content on a page
- `<head></head>`, container content to include but shouldn't be visible to web user
- `<title></title>`, sets title of page and on browser tab
- `<body></body>`, contains content visble to the web users

### Images
Images should contain the two (2) following attributes.
1. Source link to where image is stored `src="website link or file name"`
2. Alternate descriptor `alt="alternate description of image"` which is what vision impaired will hear or will show up should the image not load.

### Marking up Text
- Headings `<h1></h1>` through `<h6></h6>`, h1 being the largest, and h6 being the smallest
- Paragraphs `<p></p>`, contain text
- Lists
    - Unordered List `<ul></ul>`, denotes the list will be bulleted
    - Ordered List `<ol></ol>`, denotes the list will be numbered
    - List Item `<li></li>`, the actual content being listed
- Links `<a></a>`
    - require an href or **h**ypertext **ref**erence attribute to link to the content `href="website or area of page"`
    - content between the anchors (`<a></a>`) is what shows up as the clickable link to the web user

## Semantics
The meaning of a piece of code, in other words what is the purpose or function of that code. Basically ensure you are using the right elements for the job so that function is understood in the code that reflect what is happening with the end web user.



