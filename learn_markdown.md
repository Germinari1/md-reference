# Getting Started with Markdown 
## Let`s quickly learn some markdown.
In this document, written in Markdown (a great start, isn`t it?), we'll learn the basics of this format and develop a handy reference you can use in the future. If you want to quickly navigate to a specific part, here's a table of contents:

Parts of the document  
 1. [What is?](#whatismarkdown)
 2. [Why?](#why)
 3. [Some tools](#tools)
 4. [Syntax](#syntax)


<div id='whatismarkdown'/>  

## What is markdown ?  
Let's see what Wikipedia says:  

  >*Markdown is a lightweight markup language with plain text formatting syntax designed so that it can be converted to HTML and many other formats using a tool by the same name. Markdown is often used to format readme files, for writing messages in online discussion forums, and to create rich text using a plain text editor.*   


**Simply put**: it is another file format (just like .txt, for instance) with some special syntax for better formatting.
<div id='why'/>  

Also, there is no clearly defined Markdown standard. Different versions exists and provide some specific features. You can take a look at a list of markdown flavours [here](https://github.com/jgm/CommonMark/wiki/Markdown-Flavors). This document uses Github Flavoured Markdown.

## Why use markdown?
Some reasons :
 * **It's simple** : The syntax is so easy that you can learn in a few minutes, literally.
 * **Optimized/fast** : It saves time compared to other types of text files/formats. 
 * **Manageble** : Both the syntax and output are clean, not messy with our eyes and simple to manage.
 * **Adjust it to your needs** : With just a little set-up, your text will be translated cross any platform out there, editable in any text-editing software and convertible to a wide array of formats.
<br></br>
Also, if you ever visited a well organized GitHub repository you're probably familiar with `readme` files. Needless to say, they are super handy and written in `.md` format - that is, Markdown!  
<div id='tools'/>  

## Some tools
While any editor can do the work, some tools may be useful and make your experience more optimized.
 * **[*Stackedit*](https://stackedit.io)** : Just type normal text then use your mouse, click click done. You dont have to know the syntax.  It's good, but it will make you reliant and most developers prefers keyboards.
 * **[*Dillinger*](http://dillinger.io/)** : Online tool, support live view (split screen) and export to html. Nothing too special but very neat and handy.
 * **[*Typora*](https://www.typora.io/)** : Available for Mac and Windows, minimal, distraction free, live view seemlessly, bundled with a lot of other stuffs like Images, Lists, Tables, Code Fences, Math Blocks, YAML, Front Matters,Toc,...
 * **[*Atom*](https://atom.io/)** : popular hackable text editor (you may be using this). Yeah, this is versatile. Markdown Support? Just a part of it but is greatly built in.
 * **[*Minimalist Markdown*](https://chrome.google.com/webstore/detail/minimalist-markdown-edito/pghodfjepegmciihfhdipmimghiakcjf?hl=en)** : Chrome app. Works everywhere if you have Chrome installed.
 * **[*Macdown*](http://macdown.uranusjr.com/)** : best for Mac.
 * **[*MarkdownPad*](http://markdownpad.com/)** : best for Windows.
 * **[*Remarkable*](https://remarkableapp.github.io/)** : best for Linux. 
 * **[*GITBOOK*](http://www.gitbook.com/)** : GitBook is a modern publishing toolchain. Making both writing and collaboration easy. It does both support Markdown and have a close relation with the beloved Github.
<div id='syntax'/>  

## Markdown Syntax  
All Syntax can be found [here](https://daringfireball.net/projects/markdown/syntax). It would not be a great experience to discribe Markdown syntax in this text (the whole point is that it would be formatted, right?!), so let's get some of the basics with the table below.  

| Format        | Syntax      | Example |
| ------|-----|-----|
| Italic  	| \*Text\* 	| *This is italic* 	|
| Bold  	| \*\*Bold\*\* 	| **This is bold** 	|
| Inline links 	| \[Description text\](url here) 	| A [link](http://www.github.com) 	|
| Images 	| \![Caption\](url to img) 	| An image ![image](http://i.imgur.com/hRLuez2.png) 	|
| Link+images 	| \[\![Caption\](url to img)\](url to a page)\] 	| Click me [![me](http://i.imgur.com/hRLuez2.png)](https://www.youtube.com) 	|
| Footnotes  	| I have more \[^1\] to say.   \[^1\]: say it down here. 	| <a href="#section1">Hey,Please read the note below this table.  	|
| Line breaks 	| Double space + enter 	|  	|
| Unordered Lists 	| \* Item1     \*Item 2 	| <ul><li>item1</li><li>item2</li><li>item3</li><li>item4</li></ul> 	|
| Ordered Lists 	| 1. Item a    2. Item b 	| <ol><li>itema</li><li>itemb</li><li>itemc</li><li>itemd</li></ol>  	|
| Mixed Lists 	| 1. Item 1      * item 1a 	|  <ol><li>itema</li></ol><ul><li> item1</li></ul>	|
| Block quote 	| \> Quoted text 	|  <blockquote>Stay Hungry Stay Foolish</blockquote> 	|
| Preformatted 	| Begin each line with,two spaces or more to,make text look,e x a c t l y,like,you,type i,t. 	|   Begin each line with,two spaces or more to,make text look,e x a c t l y,like,you,type i,t. 	|
| Code 	| \`Insert Code\` 	| `printf("Hello world");` 	|
| Code block/ Syntax highlighting 	| \`\`\`insert code\`\`\` 	|  <a href="#section1">Hey,Please read the note below this table. 	|
| Headers 	| \#, \##, \###, \####, \#####, \###### (from h1 to h6) 	|  <h3>This is a h3 header</h3>	|
| Strike through 	| \~~Insert text here\~~ 	| ~~I am dead~~ 	|
| Tables 	| \| Tables   \|      Are      \|  Cool \| \|\----------\|\:\-------------\:\|------\:\| \| col 1 is\|  left-aligned \| $1600 \| | ![](http://i.imgur.com/EItt7mh.png) |
|Footnotes| Footnote[\^1\] <br> [\^1\]: Text reference | Here is a simple footnote[^1]. With some additional text after it. | 
[^1]: My footnote reference.
 
<br></br>
 <br></br>
 <p id="section1">Note: Footnotes actually do not render properly in table, but they look like this </p>  
 
 ![](http://i.imgur.com/pmeBr28.png)  
   <br></br>
   The same goes for `block code/syntax hightlighting`. That's how they look like:
  
![](http://i.imgur.com/z8KrxAz.png).    

Finally, keep in mind that some specific features or characteristics may be dependent on the markdown flavor you use.


## Notes to keep in mind:
 * Markdown allows you to use backslash escapes to generate literal characters which
would otherwise have special meaning in Markdown’s formatting syntax. One commonly used backslash escape character is : \     
 `So? \*This\* isnt italic  anymore but is surrounded by literal asterisks.`

 * Youtube videos require some additional work. 
  ```
  They can't be added directly but you can add an image with a link to the video like this:
  <a href="http://www.youtube.com/watch?feature=player_embedded&v=YOUTUBE_VIDEO_ID_HERE
  " target="_blank"><img src="http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg" 
  alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>
  ```
 * Markdown does support Emojii :laughing: :laughing: :kissing_heart: :innocent: :green_heart: ( get some emojies [here](http://www.emoji-cheat-sheet.com/) )
 * You can use \<br/> tag to force line break. 
 * Double space then enter if you want to make a new line if there is trouble making new lines.
 * Seeing is not as good as practicing. You can either create a markdown file for yourself to practice or do it online [here](http://www.markdowntutorial.com).
 *  Footnotes and syntax highlighting are not part of the original markdown and are only supported by certain flavors of markdown (Feedback from [Sean Brody](https://goo.gl/ASZwEn))
 *  Any URL (like http://www.github.com/) will be automatically converted into a clickable link.  
 *  Markdown table support is designed to handle most tables for most people; it doesn’t cover all tables for all people. If you need complex tables you will need to create them by hand or with a tool specifically designed for your output format.
 *  Using image and links, you can create some colorful assets at render time. Badges like this are typical examples that you can find all over Github  [![Java](https://img.shields.io/badge/Java-%23FFac45.svg?&style=for-the-badge&logo=java&logoColor=white&color=yellow)](https://github.com/)  [![HTML](https://img.shields.io/badge/HTML-%23FFac45.svg?&style=for-the-badge&logo=html5&logoColor=white&color=orange)](https://github.com/)
[![CSS](https://img.shields.io/badge/CSS-%23FFac45.svg?&style=for-the-badge&logo=css3&logoColor=white&color=blue)](https://github.com/)
[![JavaScript](https://img.shields.io/badge/JAVASCRIPT-%23FFac45.svg?&style=for-the-badge&logo=javascript&logoColor=white&color=yellow)](https://github.com/) 
[![Linkedin](https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/)
[![Github](http://img.shields.io/badge/github-%231877F2.svg?&style=for-the-badge&logo=github&logoColor=white&color=black)](https://github.com/)
( get some badges [here](https://shields.io/) )

* Using code block syntax with diff language to generate colored text. There are still some limitations such as can not style the text inside and few colors. This can be applicable when you want to highlight some note or to show difference between two code block

```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```


* Add beautiful note or warning section into markdown GitHub:
> **Note**:

> **Warning**:

* In markdown file on Github, with code block syntax and Mermaid language specifed, we can draw many kinds of diagram. More syntax and sample diagrams [here](https://mermaid-js.github.io/)

  - Class diagram
   ```mermaid
   classDiagram
       class Duck{
        -weight
         +swim()
         +quack()
       }
   ```
  - Sequence diagram
   ```mermaid
   sequenceDiagram
       participant dotcom
       participant iframe
       dotcom->>iframe: loads html w/ iframe url
   ```
  - Flowchart
   ```mermaid
     graph TD;
         A-->B;
         A-->C;
         B-->D;
         C-->D;
   ```

Be aware that depending on wher you are rendering this, the diagrams above might not have been rendered correctly.

## Now, it's your turn

I think this is a good place to end this document. You now have the essential knowledge to start using Markdown in your own documents, along with its interesting features. If you are a developer, a good practice is to use Markdown to write good `readme` files for your projects! Include good headings, images, and more to make it as appealing and useful as possible.