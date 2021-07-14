# Markdown Formatting Examples
A better-organized and more thorough cheatsheet can be found [here](https://www.markdownguide.org/basic-syntax).  

## Basic Formatting
#### Emphasis
Basic emphasis uses aserisks and underscores.<br><br>
`Italics can use *asterisks* or _underscores_.`  
Italics can use *asterisks* or _underscores_.<br><br>

`Bold face also uses **asterisks** or __underscores__.`  
Bold face also uses **asterisks** or __underscores__.<br><br>

`And predicatably, both approaches can be used _**together**_`  
And predicatably, both approaches can be used _**together**_.  

#### Paragraphs and blank lines
Blank lines are added using the `<br>` HTML tag, but you can also use two whitespaces at the end of the line like I do here.  

To create a paragraph insert a blank line before the paragraph text.

Using a blank line before text creates a paragraph, just like the `<p>...</p>` tags in HTML.  
    This line is supposed to be indented without being part of a list, but...  

    ...it doesn't seem to work unless it is preceded by a blank line.

***
### Headings
Headings are created by stacking hashes (`#`), with fewer hashes indicating largers headings. The largest heading uses a single hash, and the smallest uses six.<br><br>
`# This is a heading 1`  
# This is a heading 1

`## This is a heading 2`  
## This is a heading 2

`###### This is a heading 6`  
###### This is a heading 6
***
Horizontal rules (separators) can be created with three asterisks (`***`), dashes (`---`), or underscores (`___`), and they all look exactly the same.

`***`
***


`---`

---


`___`
___

***
### Links and Embedded Images

##### Simple Link
`This is how [a link](https://duckduckgo.com) is embedded.`  
This is how [a link](https://duckduckgo.com) is embedded.

##### Embedding links (with hover text)
`Here is another example, this time with hover text to describe the [link](https://duckduckgo.com "Is 'a search engine focused on privacy' an oxymoron?")`  
Here is another example, this time with hover text to describe the [link](https://duckduckgo.com "Is 'a search engine focused on privacy' an oxymoron?")  


##### ...and how to embed an image
`![10Talk Timeline](https://github.com/jessed/markdown/10talk_timeline.png)`  
![10Talk Timeline](https://github.com/jessed/markdown/blob/main/10talk_timeline.png)  


### Limitations
- Markdown does not natively support footnotes.
- Ending lines with double-spaces to create a break _usually_ works, but apparently support is a bit spotty.
- Using multiple double-space blocks at the end of a line does _not_ create additional blanks lines, for that you need to use `<br>`.
- I have not been able to successfully indent a line using four spaces, and I'm thinking support for that may not be perfect, either.
