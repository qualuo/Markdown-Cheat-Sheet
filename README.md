# Markdown Cheat Sheet

## Table of Contents  
* [Headings](#headings)  
* [Text](#text)
* [Lines](#lines)  
* [Line Breaks](#line-breaks)  
* [Links](#links)  
    * [Inline](#links)
    * [Reference](#links)
* [Images](#images)  
    * [Inline](#images)
    * [Reference](#images)
* [Lists](#lists)  
    * [Numbered](#numbered)
    * [Bulleted](#bulleted)
    * [Mixed](#mixed)
    * [Checkbox](#checkboxes)
* [Emojis](#emojis)  
* [GitHub-Flavored Markdown (GFM)](#github-flavored-markdown-gfm)
    * [Syntax Highlighting](#syntax-highlighting)  
    * [Keyboard Keys](#keyboard-keys)  
    * [Tables](#tables)
<!------------------------------------------------------------>

## Headings

# Lorem ipsum dolor sit amet, consectetur adipiscing elit.
```
# Heading 1
```
## Lorem ipsum dolor sit amet, consectetur adipiscing elit.
```
## Heading 2
``` 
### Lorem ipsum dolor sit amet, consectetur adipiscing elit.
```
### Heading 3
```
#### Lorem ipsum dolor sit amet, consectetur adipiscing elit.
```
#### Heading 4
```
##### Lorem ipsum dolor sit amet, consectetur adipiscing elit.
```
##### Heading 5
```
###### Lorem ipsum dolor sit amet, consectetur adipiscing elit.
```
###### Heading 6
```

<!------------------------------------------------------------>

## Text

***Lorem ipsum dolor sit amet, consectetur adipiscing elit.***
```
***bold & italic***
```
```
___bold & italic___
```

**Lorem ipsum dolor sit amet, consectetur adipiscing elit.**
```
**bold**
```
```
__bold__
```

_Lorem ipsum dolor sit amet, consectetur adipiscing elit._
```
*italic* 
```
```
_italic_  
```

~~Lorem ipsum dolor sit amet, consectetur adipiscing elit.~~
```
~~strikethrough~~
```

> Lorem ipsum dolor sit amet, consectetur adipiscing elit.
> >  Nunc pretium neque in eros faucibus sollicitudin.
```
> Block quote
> > Nested Block quote
```

`print("Hello World!")`
```
`inline code`
```

### Code blocks
<pre>
```
// Code block
```
</pre>

### Escape character
```
\
```


<!------------------------------------------------------------>

## Lines

___
```
___
```
***
```
***
```
---
```
---
```

<!------------------------------------------------------------>

## Line Breaks

Enter once
—> Same line
```
Enter once
—> Same line
```
Two trailing spaces + Enter once  
—> New line
```
Two trailing spaces + Enter once  
—> New line
```
Enter twice

—> New paragraph
```
Enter twice

—> New paragraph
```

<!------------------------------------------------------------>

## Links

[This is an in-line link.](https://github.com/qualuo/Markdown-Cheat-Sheet "Optional Title")
```
[Text](Link "Optional Title")  
```
[This is a reference link.][Links-1] 
```
[Text][Tag]  

[Tag]:Link   
```
[Links-1]: https://github.com/qualuo/Markdown-Cheat-Sheet
    
Tag can be any case-sensitive text, e.g. \[1], [2], [3].

#### Examples:  
Available on [GitHub](https://github.com/).
```
Available on [GitHub](https://github.com/).
```
Lorem ipsum dolor sit amet, consectetur adipiscing elit.<sup>[[1][References-1]]</sup>
Proin molestie quis urna a tristique.<sup>[[2][References-2]]</sup>

[References-1]:https://github.com/qualuo
[References-2]:https://github.com/qualuo
```
Lorem ipsum dolor sit amet, consectetur adipiscing elit.<sup>[[1][References-1]</sup>
Proin molestie quis urna a tristique.<sup>[[2][References-2]]</sup>

[References-1]:https://github.com/qualuo
[References-2]:https://github.com/qualuo
```

<!------------------------------------------------------------>

## Images

* Images are similar to Links, but have a "!" before [Text]. 
* [Text] only shows if the image failed to load and can be left empty ([]).

![This text shows if the image fails.](/Logo.png "This is an in-line image.")
```
![Text](Link "Optional Title")  
```

![This text shows if the image fails.][img1]
```
![Text][Tag]  

![Tag]:Link   
```
[img1]: /Logo.png "This is a reference image."

#### Examples:  
![Missing image.](https://avatars.githubusercontent.com/u/10774983?s=96&v=4 "I think, therefore I am.")
```
![Missing image.](https://avatars.githubusercontent.com/u/10774983?s=96&v=4 "I think, therefore I am.")
```
<!------------------------------------------------------------>

## Lists

* Indent with **4 leading spaces** to go deeper
* Start numbered list with `1.`
* Use `*`, `+`, `-` for bullet points

### Numbered 
1. First item
    1. First sub-item  
        1. First sub-sub-item  
```
1. First item
    1. First sub-item  
        1. First sub-sub-item
```

### Bulleted
* First item
    * First sub-item
        * First sub-sub-item
```
* First item
    * First sub-item  
        * First sub-sub-item
```

### Mixed
* First item
   1. First sub-item
       * First sub-sub-item
* Second item
```
* First item
    1. First sub-item  
        * First sub-sub-item
* Second item
```

### Checkboxes
* [ ] Checkbox item
* [x] Crossed checkbox item
    * [ ] Checkbox sub-item
    * [x] Crossed checkbox sub-item
```
* [ ] Checkbox item
* [x] Crossed checkbox item
    * [ ] Checkbox sub-item
    * [x] Crossed checkbox sub-item  
```

<!------------------------------------------------------------>

## Emojis

### 😂
```
:joy:
```

### Any Emoji
```
:emojiname:
```
List: https://www.webfx.com/tools/emoji-cheat-sheet/

<!------------------------------------------------------------>

## GitHub-Flavored Markdown (GFM)

Markdown spec: https://github.github.com/gfm/

### Syntax Highlighting  
(Replace "javascript" with desired language.)
<pre>
``` javascript
// Code goes here
```
</pre>

### Keyboard Keys  
Press <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>Esc</kbd> to open Task Manager.
```
<kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>Esc</kbd>
```

### Tables

Right aligned | Center aligned | Left aligned
---: | :---: | :---
Data | Data | Data
Data | Data | Data
```
Right aligned | Center aligned | Left aligned
---: | :---: | :---
Data | Data | Data
Data | Data | Data
```

<!------------------------------------------------------------>

