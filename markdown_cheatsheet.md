### Headings

Instructions: add hashtag(s) before heading label. Number of Hashtags indicates header level.

# Heading 1
## Heading 2
### Heading 3
#### Heading 4

### Bold

Instructions: encase desired text with two asterisks on each side of text block. No space separating asterisks and text.

Output:

**This is bold text**

### Italics

Instructions: encase desired text with *one* asterisk on each side of text block. No space separating asterisks and text.

Output:

*italicized text*

### Blockquote

Instructions: Set off block quotes using angle brackets. Note that line breaks in code do not automatically render line breaks in blockquote.

> Block quotes are signaled by
> Right angle brackets. Will print continuously
> (regardless of line breaks in code). <br>
> If you want to force a line break, you must end yourr line with 
> `<br>
> `

### Ordered List

1. Simply add the numeral followed by a period followed by a space
2. Item 2
3. Item 3

### Simple Code

Instructions: encase code block with one backtick at front and end. No space separating backtick from code.

`import pandas as pd`<br>

Note: this option is best when dealing with simple, short commands. <br>
If you want to add multiple lines of code, it's best to use the formatted code option (see below).

### Horizontal Rule

Instruction: type three consecutive dashes. 

Output:

---

### Links

Instructions: Title of link incased in square brackets, followed by URL encased in parantheses.
No space between right bracket and left paranethesis.

Output:

[Google](www.google.com)

### Image

Instructions: Exclamation Point, followed by alt text encased in square brackets, followed by image file in panetheses. No space between the three components.

Output:

![sample photo](George-shrimp.png)


### Table

Instructions: Use the following example as a reference:

```sh
| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |
```

Output: 

| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |


### Formatted code snippet

This is the best option when trying to format multiple lines of code. Use 'Simple Code' above when formating one line blocks or short code phrases.

Instructions: <br>
1) First line: three bacticks, followed by the letters 'sh'. No apostrophes in code. No space between backticks and letters.<br>
2) Then lines of code, divded by line breaks. <br>
3) Close with three more backticks.

Output:

```sh
cd filepathway
ls
rm file
```

### Fenced Code Block

Instructions: <br>
1) First linem, hree bacticks. <br>
2) Next line, open curly bracket. <br>
3) Next line(s) Add your key value pair(s), formatted as "key":"value", <br>
4) Next line, closed curly bracket <br>
5) Last line, three backticks <br>

Output:

``` 
{
  "firstname": "John",
  "lastname": "Smith",
  "age": "25"
}
```
   
