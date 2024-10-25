# Example Blog Post

content of the first blog post. 🌺
bing bing bing bing
Overview
Nearly all Markdown applications support the basic syntax outlined in the original Markdown design document. There are minor variations and discrepancies between Markdown processors — those are noted inline wherever possible.

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
Heading Best Practices
Markdown applications don’t agree on how to handle a missing space between the number signs (#) and the heading name. For compatibility, always put a space between the number signs and the heading name.

✅  Do this	❌  Don't do this
# Here's a Heading

#Here's a Heading
You should also put blank lines before and after a heading for compatibility.

✅  Do this	❌  Don't do this
Try to put a blank line before...

# Heading

...and after a heading.	Without blank lines, this might not look right.
# Heading
Don't do this!
Paragraphs
To create paragraphs, use a blank line to separate one or more lines of text.

Markdown	HTML	Rendered Output
I really like using Markdown.

I think I'll use it to format all of my documents from now on.	<p>I really like using Markdown.</p>

<p>I think I'll use it to format all of my documents from now on.</p>	
I really like using Markdown.

I think I'll use it to format all of my documents from now on.

Paragraph Best Practices
Unless the paragraph is in a list, don’t indent paragraphs with spaces or tabs.

 Note: If you need to indent paragraphs in the output, see the section on how to indent (tab).
✅  Do this	❌  Don't do this
Don't put tabs or spaces in front of your paragraphs.

Keep lines left-aligned like this.

    This can result in unexpected formatting problems.

  Don't add tabs or spaces in front of paragraphs.
Line Breaks
To create a line break or new line (<br>), end a line with two or more spaces, and then type return.

Markdown	HTML	Rendered Output
This is the first line.  
And this is the second line.	<p>This is the first line.<br>
And this is the second line.</p>	
This is the first line.
And this is the second line.

Line Break Best Practices
You can use two or more spaces (commonly referred to as “trailing whitespace”) for line breaks in nearly every Markdown application, but it’s controversial. It’s hard to see trailing whitespace in an editor, and many people accidentally or intentionally put two spaces after every sentence. For this reason, you may want to use something other than trailing whitespace for line breaks. If your Markdown application supports HTML, you can use the <br> HTML tag.

For compatibility, use trailing white space or the <br> HTML tag at the end of the line.

There are two other options I don’t recommend using. CommonMark and a few other lightweight markup languages let you type a backslash (\) at the end of the line, but not all Markdown applications support this, so it isn’t a great option from a compatibility perspective. And at least a couple lightweight markup languages don’t require anything at the end of the line — just type return and they’ll create a line break.

✅  Do this	❌  Don't do this
First line with two spaces after.  
And the next line.

First line with the HTML tag after.<br>
And the next line.

First line with a backslash after.\
And the next line.

First line with nothing after.
And the next line.
