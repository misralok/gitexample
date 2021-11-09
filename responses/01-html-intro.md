### What is HTML?

HTML stands for **H**yper **T**ext **M**arkup **L**anguage. HTML is not a *programming* language. It is the standard *markup* language for documents designed to be displayed in a web browser. It is simply a way to describe the structure of your website (for example defining paragraphs, headings, and data tables, or embedding images and videos in a page). Your web browser reads the HTML document and displays it in the window.


### Why learn HTML?

When most people learn to code, they start with HTML. We learn HTML to make informative, structured websites to present both links and information to an audience.

### What are HTML Elements?
HTML documents are text files made up of HTML **elements**. An HTML element contains an opening tag and a closing tag with content in between.

In this pull request, we are creating an html document called `index.html`. If we were to open this file in our browser, the body of the page would display "Hello World!". Click on the files changed` tab to view its contents.

<!DOCTYPE html>
<html>

<head>
<title>Page Title</title>
</head>

<body>
   <p>hello world!</p>
</body>

</html>

<screenshot of what our web page looks like>


The first item at the top of any HTML file is the doctype. The <!DOCTYPE html> declaration tells the browser that this document is HTML5.

Let's identify the HTML elements in this file.
- The <html> element is the root element of an HTML page
- The <head> element contains metadata which is data about the HTML document, including the <title> element as described below.
- The <title> element defines a title in the browser tab as well as for the page in search engine results.
- The <body> element contains the content of the page visible to the user.
- The <p> element defines a paragraph.

**Nested Elements**

You probably have noticed that HTML elements are contained within other HTML elements. The elements inside of other elements are known as nested elements. For example using elements listed in our file, the <title> element is always nested in the <html> element. And any <p> element will always be inside the <body> element.

**Other Elements**

If you'd like to learn about other HTML elements, check out [this documentation](https://developer.mozilla.org/en-US/docs/Web/HTML/Element).

**`.html` file extension**

Lastly, notice how the file names end in `.html`. All html documents end in .html.

### Activity: Merge this pull request

Merge this PR to add the html file to this repository. I will respond with a link to a new pull request so we can learn about JavaScript.
