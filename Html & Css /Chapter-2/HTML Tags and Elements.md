# Chapter 2: HTML Tags and Elements

In Chapter 1, we covered the basics of HTML and explored some fundamental tags and elements. In this chapter, we will dive deeper into HTML tags and elements, learning about their usage and functionality. By the end of this chapter, you will have a comprehensive understanding of various HTML tags and how to use them effectively in your web pages.

## Text Formatting Tags

HTML provides a set of tags that allow you to format and style your text. Let's take a look at some commonly used text formatting tags:

- `<strong>`: Represents strong importance, typically displayed as bold.
- `<em>`: Indicates emphasis, typically displayed in italic.
- `<u>`: Underlines the enclosed text.
- `<s>`: Renders the enclosed text with a strikethrough effect.
- `<code>`: Displays inline code snippets.
- `<blockquote>`: Defines a long quotation.

Here's an example of how these tags can be used:

```html
<p>HTML is <strong>awesome</strong> and <em>powerful</em>!</p>
<p><u>Underline</u> and <s>strikethrough</s> effects can be useful.</p>
<p>Inline code: Use the <code>&lt;code&gt;</code> tag for code snippets.</p>
<blockquote>
  "The only way to do great work is to love what you do." - Steve Jobs
</blockquote>
```

## HTML Lists

HTML provides two types of lists: ordered lists (`<ol>`) and unordered lists (`<ul>`). Let's see how these lists can be created:

```html
<h3>Ordered List:</h3>
<ol>
  <li>First item</li>
  <li>Second item</li>
  <li>Third item</li>
</ol>

<h3>Unordered List:</h3>
<ul>
  <li>Red</li>
  <li>Green</li>
  <li>Blue</li>
</ul>
```

You can also create nested lists by simply adding additional `<ol>` or `<ul>` tags within the list items.

## HTML Links and Anchors

Links, also known as anchors, are a crucial element of the web. They allow users to navigate between different web pages. Let's explore how to create links in HTML:

```html
<p>Visit <a href="https://www.example.com">Example Website</a> for more information.</p>
```

In the above example, we use the `<a>` tag to create a link. The `href` attribute specifies the URL to which the link points.

## HTML Images

Images play a vital role in web design, enhancing the visual appeal of a web page. Let's see how to insert images using the `<img>` tag:

```html
<img src="image.jpg" alt="Description of the image">
```

The `src` attribute specifies the path to the image file, and the `alt` attribute provides a text description of the image for accessibility purposes.

## HTML Forms

HTML forms allow users to input and submit data. They are used for various purposes, such as user registration, feedback collection, and online surveys. Let's create a simple form using HTML:

```html
<form action="/submit" method="post">
  <label for="name">Name:</label>
  <input type="text" id="name" name="name">

  <label for="email">Email:</label>
  <input type="email" id="email" name="email">

  <input type="submit" value="Submit">
</form>
```

In the above form, we have two input fields

: one for the name and another for the email. The `action` attribute specifies the URL where the form data will be submitted, and the `method` attribute determines the HTTP method (POST in this case).

## HTML Semantic Elements

HTML5 introduced a set of semantic elements that provide meaning and structure to web content. They improve accessibility and help search engines understand the document structure. Let's explore a few semantic elements:

- `<header>`: Represents the introductory content of a page or section.
- `<nav>`: Defines a container for navigation links.
- `<main>`: Represents the main content of the document.
- `<article>`: Represents a self-contained composition within a document.
- `<section>`: Defines a section in a document.
- `<footer>`: Represents the footer of a document or a section.

These elements help organize and structure your HTML code, making it more readable and meaningful.

Congratulations on completing Chapter 2! You have learned about various HTML tags and elements, expanding your knowledge of HTML and its capabilities. In the next chapter, we will explore CSS and how it can be used to style your web pages.
