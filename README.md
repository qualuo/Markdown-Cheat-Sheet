# Markdown Cheat Sheet

<!------------------------------------------------------------>

## Text

**Bold**
````
**bold**
````
````
__bold__
````
_Italics_
````
*italics* 
````
````
_italics_  
````
~~Strikethrough~~
````
~~strikethrough~~
````
> \> Blockquote
> > \> \> Nested Blockquote
````
> Blockquote
> > Nested Blockquote
````
<!------------------------------------------------------------>

## Headings

# H1
````
# H1
````
## H2
````
## H2
````    
### H3
````
### H3
````
#### H4
````
#### H4
````
##### H5
````
##### H5
````
###### H6
````
###### H6
````

<!------------------------------------------------------------>

## Lines

___
````
___
````
***
````
***
````
---
````
---
````

<!------------------------------------------------------------>

## Line breaks

Enter once
—> Same line
````
Enter once
—> Same line
````
Two trailing spaces + Enter once  
—> New line
````
Two trailing spaces + Enter once  
—> New line
````
Enter twice

—> New paragraph
````
Enter twice

—> New paragraph
````

<!------------------------------------------------------------>

## Links

[This is an in-line link.](https://github.com/qualuo/Markdown-Cheat-Sheet "Optional Title")

    [Text](Link "Optional Title")  

[This is a reference link.][1] 

    [Text][Tag]  

    [Tag]: Link   
    
[1]: https://github.com/qualuo/Markdown-Cheat-Sheet
    
Tag can be any case-sensitive text, e.g. \[1], [2], [3].

<!------------------------------------------------------------>

## Images

![This text shows if the image fails.](https://avatars.githubusercontent.com/u/10774983?s=96&v=4 "This is an in-line image.")

    ![Text](Link "Optional Title")  


![This text shows if the image fails.][img1]

    ![Text][Tag]  

    ![Tag]: Link   

[img1]: https://avatars.githubusercontent.com/u/10774983?s=96&v=4 "This is a reference image."

Images are similar to Links, but have a "!" before [Text]. [Text] shows if the image failed to load.

<!------------------------------------------------------------>

## Lists

* Indent with **4 leading spaces** to go deeper.  
* Start numbered list with "1."  
* Use asterisk (*), plus (+), or minus (-) for bullet points.

Numbered:  
1. First item
    1. First sub-item  
        1. First sub-sub-item  
````
1. First item
    1. First sub-item  
        1. First sub-sub-item
````

Bulleted:  
* First item
    * First sub-item
        * First sub-sub-item
````
* First item
    * First sub-item  
        * First sub-sub-item
````

Mixed:
* First item
   1. First sub-item
       * First sub-sub-item
* Second item
````
* First item
    1. First sub-item  
        * First sub-sub-item
* Second item
````
