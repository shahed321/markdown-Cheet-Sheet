Headings
To create a heading, add number signs (#) in front of a word or phrase. The number of number signs you use should correspond to the heading level. For example, to create a heading level three (<h3>), use three number signs (e.g., ### My Header).

Markdown	HTML	Rendered Output
# Heading level 1	<h1>Heading level 1</h1>	
Heading level 1
## Heading level 2	<h2>Heading level 2</h2>	
Heading level 2
### Heading level 3	<h3>Heading level 3</h3>	
Heading level 3
#### Heading level 4	<h4>Heading level 4</h4>	
Heading level 4
##### Heading level 5	<h5>Heading level 5</h5>	
Heading level 5
###### Heading level 6	<h6>Heading level 6</h6>	
Heading level 6
Alternate Syntax
Alternatively, on the line below the text, add any number of == characters for heading level 1 or -- characters for heading level 2.

Markdown	HTML	Rendered Output
Heading level 1
===============	<h1>Heading level 1</h1>	
Heading level 1
Heading level 2
---------------	<h2>Heading level 2</h2>	
Heading level 2
Paragraphs
To create paragraphs, use a blank line to separate one or more lines of text. You should not indent paragraphs with spaces or tabs.

Markdown	HTML	Rendered Output
I really like using Markdown.

I think I'll use it to format all of my documents from now on.	<p>I really like using Markdown.</p>

<p>I think I'll use it to format all of my documents from now on.</p>	
I really like using Markdown.

I think I'll use it to format all of my documents from now on.

Line Breaks
To create a line break (<br>), end a line with two or more spaces, and then type return.

Markdown	HTML	Rendered Output
This is the first line.  
And this is the second line.	<p>This is the first line.<br>
And this is the second line.</p>	
This is the first line.
And this is the second line.

Emphasis
You can add emphasis by making text bold or italic.

Bold
To bold text, add two asterisks or underscores before and after a word or phrase. To bold the middle of a word for emphasis, add two asterisks without spaces around the letters.

Markdown	HTML	Rendered Output
I just love **bold text**.	I just love <strong>bold text</strong>.	I just love bold text.
I just love __bold text__.	I just love <strong>bold text</strong>.	I just love bold text.
Love**is**bold	Love<strong>is</strong>bold	Loveisbold
Italic
To italicize text, add one asterisk or underscore before and after a word or phrase. To italicize the middle of a word for emphasis, add one asterisk without spaces around the letters.

Markdown	HTML	Rendered Output
Italicized text is the *cat's meow*.	Italicized text is the <em>cat's meow</em>.	Italicized text is the cat’s meow.
Italicized text is the _cat's meow_.	Italicized text is the <em>cat's meow</em>.	Italicized text is the cat’s meow.
A*cat*meow	A<em>cat</em>meow	Acatmeow
Bold and Italic
To emphasize text with bold and italics at the same time, add three asterisks or underscores before and after a word or phrase.

Markdown	HTML	Rendered Output
This text is ***really important***.	This text is <strong><em>really important</em></strong>.	This text is really important.
This text is ___really important___.	This text is <strong><em>really important</em></strong>.	This text is really important.
This text is __*really important*__.	This text is <strong><em>really important</em></strong>.	This text is really important.
This text is **_really important_**.	This text is <strong><em>really important</em></strong>.	This text is really important.
Blockquotes
To create a blockquote, add a > in front of a paragraph.

> Dorothy followed her through many of the beautiful rooms in her castle.
The rendered output looks like this:

Dorothy followed her through many of the beautiful rooms in her castle.

Blockquotes with Multiple Paragraphs
Blockquotes can contain multiple paragraphs. Add a > on the blank lines between the paragraphs.

> Dorothy followed her through many of the beautiful rooms in her castle.
>
> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.
The rendered output looks like this:

Dorothy followed her through many of the beautiful rooms in her castle.

The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

Nested Blockquotes
Blockquotes can be nested. Add a >> in front of the paragraph you want to nest.

> Dorothy followed her through many of the beautiful rooms in her castle.
>
>> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.
The rendered output looks like this:

Dorothy followed her through many of the beautiful rooms in her castle.

The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

Blockquotes with Other Elements
Blockquotes can contain other Markdown formatted elements. Not all elements can be used — you’ll need to experiment to see which ones work.

> #### The quarterly results look great!
>
> - Revenue was off the chart.
> - Profits were higher than ever.
>
>  *Everything* is going according to **plan**.
The rendered output looks like this:

The quarterly results look great!
Revenue was off the chart.
Profits were higher than ever.
Everything is going according to plan.

Lists
You can organize items into ordered and unordered lists.

Ordered Lists
To create an ordered list, add line items with numbers followed by periods. The numbers don’t have to be in numerical order, but the list should start with the number one.

Markdown	HTML	Rendered Output
1. First item
2. Second item
3. Third item
4. Fourth item	<ol>
<li>First item</li>
<li>Second item</li>
<li>Third item</li>
<li>Fourth item</li>
</ol>	
First item
Second item
Third item
Fourth item
1. First item
1. Second item
1. Third item
1. Fourth item	<ol>
<li>First item</li>
<li>Second item</li>
<li>Third item</li>
<li>Fourth item</li>
</ol>	
First item
Second item
Third item
Fourth item
1. First item
8. Second item
3. Third item
5. Fourth item	<ol>
<li>First item</li>
<li>Second item</li>
<li>Third item</li>
<li>Fourth item</li>
</ol>	
First item
Second item
Third item
Fourth item
1. First item
2. Second item
3. Third item
    1. Indented item
    2. Indented item
4. Fourth item	<ol>
<li>First item</li>
<li>Second item</li>
<li>Third item
<ol>
<li>Indented item</li>
<li>Indented item</li>
</ol>
</li>
<li>Fourth item</li>
</ol>	
First item
Second item
Third item
Indented item
Indented item
Fourth item
Unordered Lists
To create an unordered list, add dashes (-), asterisks (*), or plus signs (+) in front of line items. Indent one or more items to create a nested list.

Markdown	HTML	Rendered Output
- First item
- Second item
- Third item
- Fourth item	<ul>
<li>First item</li>
<li>Second item</li>
<li>Third item</li>
<li>Fourth item</li>
</ul>	
First item
Second item
Third item
Fourth item
* First item
* Second item
* Third item
* Fourth item	<ul>
<li>First item</li>
<li>Second item</li>
<li>Third item</li>
<li>Fourth item</li>
</ul>	
First item
Second item
Third item
Fourth item
+ First item
* Second item
- Third item
+ Fourth item	<ul>
<li>First item</li>
<li>Second item</li>
<li>Third item</li>
<li>Fourth item</li>
</ul>	
First item
Second item
Third item
Fourth item
- First item
- Second item
- Third item
    - Indented item
    - Indented item
- Fourth item	<ul>
<li>First item</li>
<li>Second item</li>
<li>Third item
<ul>
<li>Indented item</li>
<li>Indented item</li>
</ul>
</li>
<li>Fourth item</li>
</ul>	
First item
Second item
Third item
Indented item
Indented item
Fourth item
Adding Elements in Lists
To add another element in a list while preserving the continuity of the list, indent the element four spaces or one tab, as shown in the following examples.

Paragraphs
*   This is the first list item.
*   Here's the second list item.

    I need to add another paragraph below the second list item.

*   And here's the third list item.
The rendered output looks like this:

This is the first list item.
Here’s the second list item.

I need to add another paragraph below the second list item.

And here’s the third list item.
Blockquotes
*   This is the first list item.
*   Here's the second list item.

    > A blockquote would look great below the second list item.

*   And here's the third list item.
The rendered output looks like this:

This is the first list item.
Here’s the second list item.

A blockquote would look great below the second list item.

And here’s the third list item.
Code Blocks
Code blocks are normally indented four spaces or one tab. When they’re in a list, indent them eight spaces or two tabs.

1.  Open the file.
2.  Find the following code block on line 21:

        <html>
          <head>
            <title>Test</title>
          </head>

3.  Update the title to match the name of your website.
The rendered output looks like this:

Open the file.
Find the following code block on line 21:

<html>
  <head>
    <title>Test</title>
  </head>
Update the title to match the name of your website.
Images
1.  Open the file containing the Linux mascot.
2.  Marvel at its beauty.

    ![Tux, the Linux mascot](/assets/images/tux.png)

3.  Close the file.
The rendered output looks like this:

Open the file containing the Linux mascot.
Marvel at its beauty.

Tux, the Linux mascot

Close the file.
Code
To denote a word or phrase as code, enclose it in tick marks (`).

Markdown	HTML	Rendered Output
At the command prompt, type `nano`.	At the command prompt, type <code>nano</code>.	At the command prompt, type nano.
Escaping Tick Marks
If the word or phrase you want to denote as code includes one or more tick marks, you can escape it by enclosing the word or phrase in double tick marks (``).

Markdown	HTML	Rendered Output
``Use `code` in your Markdown file.``	<code>Use `code` in your Markdown file.</code>	Use `code` in your Markdown file.
Code Blocks
To create code blocks, indent every line of the block by at least four spaces or one tab.

    <html>
      <head>
      </head>
    </html>
The rendered output looks like this:

<html>
  <head>
  </head>
</html>
 Note: To create code blocks without indenting lines, use fenced code blocks.
Horizontal Rules
To create a horizontal rule, use three or more asterisks (***), dashes (---), or underscores (___) on a line by themselves.

***

---

_________________
The rendered output of all three looks identical:

Links
To create a link, enclose the link text in brackets (e.g., [Duck Duck Go]) and then follow it immediately with the URL in parentheses (e.g., (https://duckduckgo.com)).

My favorite search engine is [Duck Duck Go](https://duckduckgo.com).
The rendered output looks like this:

My favorite search engine is Duck Duck Go.

Adding Titles
You can optionally add a title for a link. This will appear as a tooltip when the user hovers over the link. To add a title, enclose it in parentheses after the URL.

My favorite search engine is [Duck Duck Go](https://duckduckgo.com "The best search engine for privacy").
The rendered output looks like this:

My favorite search engine is Duck Duck Go.

URLs and Email Addresses
To quickly turn a URL or email address into a link, enclose it in angle brackets.

<https://www.markdownguide.org>
<fake@example.com>
The rendered output looks like this:

https://www.markdownguide.org
fake@example.com

Formatting Links
To emphasize links, add asterisks before and after the brackets and parentheses.

I love supporting **[EFF](https://eff.org)**.
This is the *[Markdown Guide](https://www.markdownguide.org)*.
The rendered output looks like this:

I love supporting the EFF.
This is the Markdown Guide.

Reference-style Links
Reference-style links are a special kind of link that make URLs easier to display and read in Markdown. Reference-style links are constructed in two parts: the part you keep inline with your text and the part you store somewhere else in the file to keep the text easy to read.

Formatting the First Part of the Link
The first part of a reference-style link is formatted with two sets of brackets. The first set of brackets surrounds the text that should appear linked. The second set of brackets displays a label used to point to the link you’re storing elsewhere in your document.

Although not required, you can include a space between the first and second set of brackets. Also, the label in the second set of brackets is not case sensitive and can include letters, numbers, spaces, or punctuation.

This means the following example formats are all roughly equivalent for the first part of the link:

[hobbit-hole][1]
[hobbit-hole] [1]
[hobbit-hole][a]
[hobbit-hole][A]
Formatting the Second Part of the Link
The second part of a reference-style link is formatted with the following attributes:

The label, in brackets, followed immediately by a colon and at least one space (e.g., [label]: ).
The URL for the link, which you can optionally enclose in angle brackets.
The optional title for the link, which you can enclose in double quotes, single quotes, or parentheses.
This means the following example formats are all roughly equivalent for the second part of the link:

[hobbit-hole]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle
[hobbit-hole]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle "Hobbit lifestyles"
[hobbit-hole]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle 'Hobbit lifestyles'
[hobbit-hole]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle (Hobbit lifestyles)
[hobbit-hole]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> "Hobbit lifestyles"
[hobbit-hole]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> 'Hobbit lifestyles'
[hobbit-hole]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> (Hobbit lifestyles)
You can place this second part of the link anywhere in your Markdown document. Some people place them immediately after the paragraph in which they appear while other people place them at the end of the document (like endnotes or footnotes).

An Example Putting the Parts Together
Say you add a URL as a standard URL link to a paragraph and it looks like this in Markdown:

In a hole in the ground there lived a hobbit. Not a nasty, dirty, wet hole, filled with the ends
of worms and an oozy smell, nor yet a dry, bare, sandy hole with nothing in it to sit down on or to
eat: it was a [hobbit-hole](https://en.wikipedia.org/wiki/Hobbit#Lifestyle "Hobbit lifestyles"), and that means comfort.
Though it may point to interesting additional information, the URL as displayed really doesn’t add much to the existing raw text other than making it harder to read. To fix that, you could format the URL like this instead:

In a hole in the ground there lived a hobbit. Not a nasty, dirty, wet hole, filled with the ends
of worms and an oozy smell, nor yet a dry, bare, sandy hole with nothing in it to sit down on or to
eat: it was a [hobbit-hole][1], and that means comfort.

[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> "Hobbit lifestyles"
In both instances above, the rendered output would be identical:

In a hole in the ground there lived a hobbit. Not a nasty, dirty, wet hole, filled with the ends of worms and an oozy smell, nor yet a dry, bare, sandy hole with nothing in it to sit down on or to eat: it was a hobbit-hole, and that means comfort.

and the HTML for the link would be:

<a href="https://en.wikipedia.org/wiki/Hobbit#Lifestyle" title="Hobbit lifestyles">hobbit-hole</a>
Images
To add an image, add an exclamation mark (!), followed by alt text in brackets, and the path or URL to the image asset in parentheses. You can optionally add a title after the URL in the parentheses.

![Philadelphia's Magic Gardens. This place was so cool!](/assets/images/philly-magic-gardens.jpg "Philadelphia's Magic Gardens")
The rendered output looks like this:

Philadelphia's Magic Gardens. This place was so cool!

Linking Images
To add a link to an image, enclose the Markdown for the image in brackets, and then add the link in parentheses.

[![An old rock in the desert](/assets/images/shiprock.jpg "Shiprock, New Mexico by Beau Rogers")](https://www.flickr.com/photos/beaurogers/31833779864/in/photolist-Qv3rFw-34mt9F-a9Cmfy-5Ha3Zi-9msKdv-o3hgjr-hWpUte-4WMsJ1-KUQ8N-deshUb-vssBD-6CQci6-8AFCiD-zsJWT-nNfsgB-dPDwZJ-bn9JGn-5HtSXY-6CUhAL-a4UTXB-ugPum-KUPSo-fBLNm-6CUmpy-4WMsc9-8a7D3T-83KJev-6CQ2bK-nNusHJ-a78rQH-nw3NvT-7aq2qf-8wwBso-3nNceh-ugSKP-4mh4kh-bbeeqH-a7biME-q3PtTf-brFpgb-cg38zw-bXMZc-nJPELD-f58Lmo-bXMYG-bz8AAi-bxNtNT-bXMYi-bXMY6-bXMYv)
The rendered output looks like this:

An old rock in the desert

Escaping Characters
To display a literal character that would otherwise be used to format text in a Markdown document, add a backslash (\) in front of the character.

\* Without the backslash, this would be a bullet in an unordered list.
The rendered output looks like this:

* Without the backslash, this would be a bullet in an unordered list.

Characters You Can Escape
You can use a backslash to escape the following characters.

Character	Name
\	backslash
`	tick mark
*	asterisk
_	underscore
{}	curly braces
[]	brackets
()	parentheses
#	pound sign
+	plus sign
-	minus sign (hyphen)
.	dot
!	exclamation mark