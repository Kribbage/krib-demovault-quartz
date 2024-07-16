---
courseid: 2
---

#obsidiancourse 


# What is markdown

Markdown is how Obsidian and many other text editors format text. 

- It uses special characters to mark plain text, for example
```markdown
**bold** _italic_ ~~strikethrough~~ 
```

>resulting in
	  **bold**    _italic_  ~~strikethrough~~   


- As opposed to something like Microsoft Word which uses proprietary "rich text" formats which are encoded text, are not always cross-compatible and can become obsolete.

- Plain text and by consequence markdown will be around for as long as your files are, and can always be repurposed for whatever app you happen to be using. That does still mean you have to be careful with your files and back them up!

- Obsidian has many shortcuts that help you format markdown text, as well as a live preview mode that shows you the formatted result as you are typing so you don't always have to remember the syntax. This makes it feel much more like a rich text editor


## Some more markdown

### headers

> headers and sub-headers make up sections of the text and can be linked to directly or searched for. You can also collapse content under a header by clicking the little arrow next to it. Note that these are hierarchical - meaning the number of #### used indicate levels of hierarchy 

#### sub headers

- code blocks
```markdown
"```"
these markers (3 grave or backticks at the start and end) create a code block that ignores any markdown formatting. (you may need to click into this block in editing view to see the correct syntax) you can use special characters if needed and even hightlight syntax of coding languages. There are also plugins that can render special content defined inside these code blocks.
"```"
```

- Lists 
```markdown
- unordered list item 1
- unordered list item 2

1. ordered list item 1
2. ordered list item 2



```

- embed and image 
> you can just drag it onto your page as well or copy and paste

```
![[filenameofimageingyourvault.jpg]]

^ note the exclamation point that signifies embedding 
```
![[Red_Panda_(24986761703).jpg]]
😻 <- emojis work too ( win+. or cmd+ctrl+space )

### Blockquotes

>Need to quote some information? use a '>' hitting enter will continue it 
>to the 
>next 
>line a second enter will exit


### Callouts 

>[!abstract] Callouts 
>Callouts are a special kind of block quote that stand out more and have several icons you can select by using a corresponding keyword in brackets at the start. For example '>[!info]' or '>[!abstract]'

[Callouts - Obsidian Help](https://help.obsidian.md/Editing+and+formatting/Callouts#Supported+types) <- external link to obsidian documentation with a list of types of callouts

### Tables

>Tables are kind of annoying to create with the default setup in obsidian. There are some plugin s like 'markdown table editor'  and the advanced tables plugin that help make it easier.

```markdown
| column 1 | colunmn 2 | column 3 | 
| -------- | --------- |  ------- | 
| value    | value 2   | value 3  | 
```
| column 1 | colunmn 2 | column 3 | 
| -------- | --------- |  ------- | 
| value    | value 2   | value 3  | 

### Footnotes 

```
footnotes are numbered automatically
	a footnoted item^[the footnote inline]
	a footnote item^[the footnote inline] 
	a second footnote item[^1]
	a second footnote item[^1]
  the number used is irrelevant they will be assigned automatically
non-inline footnote definitions are defined at the bottom of the document
	[^1]:this is the footnote

```


### Links

#### external links

```markdown
[Callouts](https://help.obsidian.md/Editing+and+formatting/Callouts#Supported+types)
```

#### internal links


Links are a very important part of how we build our network of notes, lets link to another note in our vault to go over them.

```markdown
[[the name of your note file here | < you can put this bar then anything else]] 

two square brackets with a file name in the middle. The 'anything else' section will be how the link appears instead of the file name
```

[[links example|anything else]]
