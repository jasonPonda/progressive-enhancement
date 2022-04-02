# progressive-enhancement

## This project was carried out in an educational context.

### 1. HTML is about semantics

What is "semantics" ?

A sentence is a series of words. A title is also a series of words. And so is a subtitle. How can a computer know which is which? Semantics is about marking up what a series of information is to be considered as. It adds hierarchy and structure to a text. That's what HTML is for.

To make proper HTML code, one must think not about the looks of the text, but of its structure 💖.

How ? When writing html code, ask yourself this question: "What is this series of words : a date ? A title? A paragraph? A legend? A caption describing an image ? And this series of sentences, is this a chapter ? A footnote ?" the answer to that question will tell you which HTML tag to best use to describe the content.

Why is semantics so important ?
Two reasons : SEO (your website's findability / visibility on Google) and Accessibility (make sure all humans, no matter their handicap (blindness, poor eyesight, colorblindness) can access the information.

1.1 SEO
The ultimate goal of a search engine like Google is to return to a human the best possible results for what they have searched for (a few words). To do this, Google creates software such as Googlebot, which indexes content found on the web by following links from one page to another, from one site to another. (That's why we sometimes talk about web spiders).

Using powerful algorithms, Google reads and analyzes the HTML content of each page found, in order to "understand" what it is talking about thanks to its html structure (title, subtitle, list, etc.). This allows Google to determine what each page is about, and if it seems to match the search, it will return it to the user as one of the first results.

Therefore, if our pages are not very semantic, Google will not show them, and your sites, no matter how cool they look and feel, will not have any traffic.

Findability Precedes Usability In the Alphabet and on the Web. You Can't Use What You Can't Find. – Peter Morville

1.2 Accessibility
The web is a universal project: everyone must have access to content. Including the blind and visually impaired (you, one day). Blind people use "screen readers" that use html code to tell the story aloud. If your html code is not semantic, the page will not make much sense to listen to (even if it looks good). Feel free to[test on your own computer] (https://stackoverflow.com/a/43368748/53960).

Semantic is actually pretty easy.
Semantics consists in choosing the right tags and attributes to represent your content. Do keep in mind that too much semantics hurts semantics. The rule (as often in programming) is: as little code as possible, but as much as necessary.

Tags
Tags are used to indicate the semantic function of a portion of content in "blocks". Most html blocks work with an opening tag and a closing tag.

Syntax example :

<p>This is a paragraph (hence the P letter).</p>
Exercices :

Translate this txt document into semantic html, using the right html tags : h1, h2, blockquote, q, img, img, hr, figure and caption, table, th, tr, td, ul or ol andli.
No div or span: they do not provide any semantics.
Find, for each of these tags, the origin of their name (that's how we remember them). If in doubt, look for the answer on html5doctor.com.
Add two or three links of your choice in the html page via the tag a
Is there a part that could be considered as a header? If so, group it in a header tag.
And a footer? If so, group this content together in a footer tag
Put all instances of the words "Maybe" in a em or strong tag.
Html attributes
They are used to define the characteristics of the tags. Imagine that there is a "human" tag.

<p>
Steven Paul Jobs, known as Steve Jobs, (San Francisco, February 24, 1955 - Palo Alto, October 5, 2011) is an entrepreneur...
</p>
We can, with attributes, describe this human being to differentiate him from others.

<p class="human" name="Steve Job" nationality="USA" origin="Syria" job="CEO" company="Apple" hair="grey">
Steven Paul Jobs, known as Steve Jobs, (San Francisco, February 24, 1955 - Palo Alto, October 5, 2011) is an entrepreneur...
</p>
In this way, by increasing the semantics of the tags with attributes, we have clarified for a machine that is this human being.

Here is a one-line summary of the syntax of tags, attributes and values:

<tag attribute="value">content</tag> 

### 2. CSS is to improve the visual look
CSS is a computer language that allows you to control the visual aspect of your content. For example, you can control the appearance of the text via these properties: font-style, font-size, color, line-height.

In other words, if html allows you to structure content, CSS allows you to put some makeup on it, making it more visually attractive.

### 3. Web fonts
By default, the browser uses the fonts installed on the client's computer. However, you can use specific fonts: the webfonts.

### 4. Useful tools
Check that your HTML is valid via the w3c validator
Check that your HTML allows good organic SEO, via other tools like the Google Lighthouse Test
