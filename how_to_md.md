# A quick guide for writing Markdown

This is a quick and easy-to-follow guide on how to write a webpage using only markdown.

## What is Markdown?

Markdown is a lightweight, easy-to-read markup language created in 2004 by John Gruber that uses plain text formatting syntax to structure documents. It allows users to create formatted text (bold, headers, lists) using simple punctuation marks, which is then converted into HTML for web display.

## Step 1: Create a Markdown file

To create a new markdown file, simply open your favourite text editor and create a new file.
Choose an appropriate name and add ".md" at the end or select "markdown" as datatype.

## Step 2: Write a heading

A good website always starts with a heading!
To add one to your newly created markdown file, simply type "# " + whatever you want your heading to be.

```markdown
# Heading 1
```

This is called a level 1 heading, it will be interpreted as a "h1" element.

## Step 3: Write a paragraph

Now that you have successfully created your first heading, it's time to fill your webpage with content. The content of your webpage should be written in seperate paragraphs for proper readability and comprehensibility.

To separate two paragraphs, simply leave a blank line in between.

```markdown
This is a paragraph.

This is another paragraph
```

A paragraph will be interpreted as a "p" element.

## Step 4: Separate your paragraphs with Subheading

Now that your webpage is full of paragraphs it is time to separate them using subheadings. Luckily these work just like the heading you wrote in step 2! Simply type "## " + whatever you want your subheading to be. Just like paragraphs, subheading should be separated with blank lines for compatibility.

```markdown
# Heading 1

## Heading 2
```

This is called a level 2 heading, it will be interpreted as a "h2" element.

As you probably already assumed, there are even more levels to headings in markdown. You can use up to six different levels, to improve readybility!

```markdown
# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6
```

## Step 5: Adding Emphasis to sections

To make parts of your text stand out, you can add emphasis to it. **Bold** and *italic* are the two emphases available in markdown. Simply enclose the parts you want to emphasize with one, two or three asterisks.

### Bold

```markdown
Adding **emphases** to your page is awesome!
```

### Italic

```markdown
Adding *emphases* to your page is awesome!
```

### Bold + Italic

```markdown
Adding ***emphases*** to your page is awesome!
```

## Step 6: Quotation

If you want to include quotes, markdown has got you covered! Not only can you add quotes from your favourite book, it's also possible to display source code from a large number of programming languages with beautiful syntax highlighting.

### Blockquotes

Blockquotes are very useful if you want to display plain text as a quotation.
Simply add ">" to the beginning of each line of your quote.

```markdown
>This is the first line of the quote!
>
>This is the last line of the quote!
```

### Source code quotes

If you want to display source code with syntax highlighting, simply enclose the code with three backticks, make sure to declare what kind of code it is by writing the name of the language after your first three backticks with **no space character** in between.

````markdown
```markdown
# headline 1

This is an example paragraph!
```
````

## view a code example
[code example](/code_example.html "code example")

## go back to main page
[main page](/index.html "main page")