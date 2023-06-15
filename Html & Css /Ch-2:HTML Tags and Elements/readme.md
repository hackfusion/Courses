# Chapter 2: HTML Tags and Elements

In the previous chapter, we introduced you to the basics of HTML, including the structure of an HTML document and some commonly used tags. In this chapter, we will delve deeper into HTML tags and elements, exploring their functionalities and usage in more detail.

## Text Formatting Tags

HTML provides various tags to format and style text within your web pages. Let's look at some commonly used text formatting tags:

- `<strong>`: This tag is used to emphasize important text and render it in a bold font.
- `<em>`: The `<em>` tag is used to emphasize text and render it in an italicized font.
- `<u>`: The `<u>` tag is used to underline text.
- `<s>`: This tag is used to strike through text to indicate that it is no longer valid or relevant.
- `<sup>`: The `<sup>` tag is used to render superscript text.
- `<sub>`: The `<sub>` tag is used to render subscript text.

Example:

```html
<p>This is a <strong>bold</strong> text example.</p>
<p>This is an <em>italicized</em> text example.</p>
<p>This is an <u>underlined</u> text example.</p>
<p>This is a <s>strikethrough</s> text example.</p>
<p>This is a math equation: 10<sup>2</sup> + 5<sub>2</sub>.</p>
```

## Links and Anchors

Links play a crucial role in web development, allowing users to navigate between web pages. HTML provides the `<a>` tag to create hyperlinks. Let's see how it works:

```html
<a href="https://www.example.com">Visit Example Website</a>
```

In the above example, the text "Visit Example Website" serves as the anchor text, and the `href` attribute specifies the destination URL.

You can also create links within the same webpage by using the `id` attribute to target specific elements and the `#` symbol as the URL:

```html
<a href="#section2">Jump to Section 2</a>

<h2 id="section2">Section 2</h2>
```

In this example, clicking on the "Jump to Section 2" link will scroll the page to the element with the `id` of "section2."

## Images

Images are essential for enhancing the visual appeal of web pages. The `<img>` tag is used to display images. It requires the `src` attribute to specify the image source (URL or file path) and the `alt` attribute to provide alternative text for screen readers and in case the image fails to load:

```html
<img src="image.jpg" alt="Image description">
```

You can also adjust the width and height of the image using the `width` and `height` attributes:

```html
<img src="image.jpg" alt="Image description" width="300" height="200">
```

## Lists

HTML offers two types of lists: ordered lists (`<ol>`) and unordered lists (`<ul>`).

### Ordered Lists

Ordered lists are used when the order of items is important. Each list item is wrapped in an `<li>` tag:

```html
<ol>
  <li>First item</li>
  <li>Second item</li>
  <li>Third item</li>
</ol>
```

### Unordered Lists

Unordered lists are used when the order of items is not important. Each list item is wrapped in an `<li>` tag:

```html
<ul>
  <li>Red</li>
  <li>

Green</li>
  <li>Blue</li>
</ul>
```

## HTML Tasks

To reinforce your understanding of HTML tags and elements, here are some tasks for you to complete:

1. Create a new HTML document.
2. Add a heading that says "Text Formatting Example."
3. Use appropriate text formatting tags to emphasize certain words or phrases.
4. Create a section with the heading "Links" and add a hyperlink to your favorite website.
5. Insert an image of your choice and provide a suitable `alt` attribute.
6. Create an ordered list of your favorite books or movies.
7. Create an unordered list of items you need for a picnic.
8. Experiment with different text formatting tags, links, and images to modify the appearance of your webpage.

## HTML Questions and Answers

Q: How do you emphasize text in HTML?
A: You can use the `<strong>` tag for strong emphasis (typically displayed as bold) and the `<em>` tag for mild emphasis (typically displayed as italic).

Q: What is the purpose of the `<a>` tag in HTML?
A: The `<a>` tag is used to create hyperlinks, allowing users to navigate between web pages.

Q: How do you insert an image in HTML?
A: You can use the `<img>` tag with the `src` attribute to specify the image source and the `alt` attribute to provide alternative text.

Q: What are ordered lists and unordered lists in HTML?
A: Ordered lists (`<ol>`) are used for items with a specific order, while unordered lists (`<ul>`) are used for items without a specific order.

Q: Can you create links within the same webpage in HTML?
A: Yes, you can create links within the same webpage by using the `id` attribute to target specific elements and the `#` symbol as the URL.

Congratulations on completing Chapter 2! You have learned about HTML tags and elements for text formatting, creating links, inserting images, and working with lists. In the next chapter, we will explore the concept of structuring HTML documents to create well-organized web pages.
