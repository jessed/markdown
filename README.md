### Emphasis / Basic Formatting
Basic emphasis uses aserisks and underscores.<br><br>
`Italics can use *asterisks* or _underscores_.`  
Italics can use *asterisks* or _underscores_.<br><br>

`Bold face also uses **asterisks** or __underscores__.`  
Bold face also uses **asterisks** or __underscores__.<br><br>

`And predicatably, both approaches can be used _**together**_`  
And predicatably, both approaches can be used _**together**_.  

Blank lines are added using the `<br>` HTML tag, but you can also use two whitespaces at the end of the line like I do here.  
To create a paragraph insert a blank line.

Using a blank line before text creates a paragraph, just like the `<p>...</p>` tags in HTML.

    This line is supposed to be indented without being part of a list, but...  


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



###### Embedding links (with hover text)
`This is how [a link](https://duckduckgo.com "Duck Duck Go") is embedded.`  
This is how [a link](https://duckduckgo.com "Duck Duck Go") is embedded.

###### ...and how to embed an image
`![10Talk Timeline](https://github.com/jessed/markdown/10talk_timeline.png)`<br>
![10Talk Timeline](https://github.com/jessed/markdown/blob/main/10talk_timeline.png)


### Limitations
- Markdown does not natively support footnotes.
- Ending lines with double-spaces to create a break _usually_ works, but apparently support is a bit spotty.
- Using multiple double-space blocks at the end of a line does _not_ create additional blanks lines, for that you need to use `<br>`.
- I have not been able to successfully indent a line using four spaces, and I'm thinking support for that may not be perfect, either.
