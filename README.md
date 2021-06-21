MarkDown Language
================

What is markdown language ? It is simple markup language like html but not html. it is super set of html. So some html tag work in here as well but  it not good practice of writing markdown language. In this whole documentation to learn markdown language. How to use it and how to write documentatin by markdown language ?

:blush: So let's go

***Index***
- [Introduce](#introduce)
- [Heading](#heading)
- [Paragraph](#paragraph)
- [Line](#line)
- [FormatText](#FormatText)
- [Blockqoute](#blockqoute)
- [List](#list)
- [Link](#Link)
- [Image](#image)
- [Tabels](#tabels)
- [Codeblock](#codeblock)
- [Collapsible](#collapsible)
- [Emoji](#emoji)
- [Misc](#misc)
- [Badge](#badge)
- [Escape](#escape)
- [Comment](#comment)
- [End](#end)

## Introduce

At first I introduce the markdown language. It is one kind of markup language use for create and write documentation like this documentation. Bascally it use for write github documentation. Like this. It is super set of html but not html.

## Heading

In markdown language have 6 type of heading like html. It syntax is very easy then html.

```markdown
    # heading one
    ## heading two
    ### heading three
    #### heading four
    ##### heading five
    ###### heading six
```

This is all is heading. Another way to write heading in markdown language is 

```markdown
    heading one
    =========
    heading two
    ---------------
```

It will be heading in markdown language.

## Paragraph
In markdown language if we write anything without syntax it also call paragraph. like this. Also we line break inside the paragraph by html `<br>`.

```markdown
    This is paragraph <br>
    This is another line
```

We use paragraph inside the box. in that case use tav at first.

```markdown
        This is paragraph inside the box.
```

*Result is*<br>

    This is paragraph inside the box.

## Line
In markdown language have 3 kind of line.

```markdown
    hyphen line
    --------------------
    underline line
    _____________
    star line 
    **************
```

The result is 
--------------
--------------
__________
**********


## FormatText
Three type of format in markdown language. Bold, italic and delete or line through.

<details>
    <summary>Italic</summary>

If italice the line in that case use single _ or *. If italice the letter inside the word in that case use must *. hyphen can not work in here.

    ```markdown
        *This is italic text*<br>
        _This is another italic text_<br>
        This _word_ is italic<br>
        This lett*ER* is italic<br>
    ```
*The result*
> *This is italic text*<br>
> _This is another Italic text_<br>
> This _word_ is italic<br>
> This lett*ER* is italic<br>

</details>

<details>
    <summary>Bold</summary>

Same like italic but inthat case we use two ** star or __

    ```markdown
        **This is Bold text**<br>
        __This is another Bold text__<br>
        This __word__ is bold<br>
        This lett**ER** is bold<br>
    ```

*The result*
> **This is bold text**<br>
> __This is another bold text__<br>
> This __word__ is bold<br>
> This lett**ER** is bold<br>


</details>

<details>
    <summary>Delete</summary>

same like like bold but in that case we use two ~ ship

    ```markdown
        ~~This is delete text~~<br>
        ~~This is another delete text~~<br>
        This ~~word~~ is delete<br>
        This lett~~ER~~ is delete<br>
    ```

*The result*
> ~~This is delete text~~<br>
> ~~This is another delete text~~<br>
> This ~~word~~ is delete<br>
> This lett~~ER~~ is delete<br>


</details>

<details>
    <summary>Nested</summary>

If need multiful text format so we can use text format as well.

```markdown
    ~~*This text delete and italic*~~
    ***This text bold and italic***
```

__The Result__ <br>

    ~~*This text delete and italic*~~<br>
    ***This text bold and italic***
</details>

## Blockqoute

In markdown if need blockqoute, in that case use > this right arrow bracket

```markdown
    > This is blockqoute
```

_result:_

> This is blockqoute.

#### Nested blockqoute
What is nested blockqoute ?  blockqoute inside the another blockqoute. it call nested blockqoute. example : -

~~~markdown
> This is one level blockqoute
>> This is secound level blockqoute
>>> This is another level blcokqoute
>>
>> This is secound level blockqoute
>
>This is first level block qoute
~~~

_result:_
> This is one level blockqoute
>> This is secound level blockqoute
>>> This is another level blcokqoute
>>
>> This is secound level blockqoute
>
>This is first level block qoute

## List
There are two kind of list in markdown. Order list and unorder list.

<details>
    <summary>Order List</summary>

This is easy. just write list as we write real life. just every line start with number,do and space.

```markdown
    1. JavaScript
    2. Css
    3. Html
    4. Python 
```

_result:_

    1. JavaScript
    2. Css
    3. Html
    4. Python

number order is not important in here.example

~~~markdown
4. JavaScript
5. Css
6. Html
70. Python
~~~

_result:_

4. JavaScript
5. Css
6. Html
70. Python

</details>

<details>
    <summary>Unorder List</summary>

It create like order like but in that case use number instead use +,- and *.

~~~markdown
- Html
- Css
- markdown

* C
* C++ 
* C# 
* Objective C

+ JavaScript
+ Python
+ Java
+ PHP
+ Swift

~~~

_Result:_
- Html
- Css
- markdown

* C
* C++
* C#
* Objective C

+ JavaScript
+ Python
+ Java
+ PHP
+ Swift

</details>

<details>
<summary>Nested List</summary>
Nested list means list inside the another list. it easy to write in markdown

~~~markdown
1. JavaScript
2. Python
3. C
    + C++
    + C#
    + Objective C
4. Markup Language
    1. HTML
    2. CSS
    3. MARKDOWN
5. Swift
6. Go lang
~~~

_Result:_

    1. JavaScript
    2. Python
    3. C
        + C++
        + C#
        + Objective C
    4. Markup Language
        1. HTML
        2. CSS
        3. MARKDOWN
    5. Swift
    6. Go lang
</details>

# Link
In markdown language write link beyhind the text is easy. structure

~~~
[Name](link 'title')
~~~

_Example:_
~~~markdown
    1. [Google](https://www.google.com 'Google')
    2. [Yahoo](https://www.yahoo.com 'Yahoo')
~~~

_Result:_

    1. [Google](https://www.google.com 'Google')
    2. [Yahoo](https://www.yahoo.com 'Yahoo')

Write Mailto Link

~~~markdonw
Tazri Mail: <md.tazri@gmail.com>
~~~

_Result:_<br>

> Tazri Mail : <md.tazri@gmail.com>

create referance type link in markdown language

~~~markdown
1. [Google][1]
2. [Yahoo][2]
3. [Bing][3]

[1]: <https://www.google.com> 'Google'
[2]: <https://www.yahoo.com> 'Yahoo'
[3]: <https://www.bing.com> 'bing'
~~~

_Result:_

> 1. [Google][1]
> 2. [Yahoo][2]
> 3. [Bing][3]

[1]: <https://www.google.com> 'Google'
[2]: <https://www.yahoo.com> 'Yahoo'
[3]: <https//www.bing.com> 'bing'

## Image
Add image in markdown like write link. Just little bit differance.

~~~markdown
![Avater](./img/avater.png 'Avater')
~~~

_Result:_
<br>
![Avater](./img/avater.png 'Avater')

add link inside the image is easy. Just wrap the image by the link

~~~markdown
    [![Avater](./img/avater.png 'Avater')](https://github.com/Tazri 'Md Tazri GitHub Link')
~~~

_Result:_
<br>
<br>

[![Avater](./img/avater.png 'Avater')](https://github.com/Tazri 'Md Tazri GitHub Link')

## Tabels
Create tabels inside the markdown, in that case need | pipe sign and - hyphen sign.

~~~markdown
engine|Language|Markup
------- |----------- | ---------
Google | Python | HTML
Bing | JavaScript | Css
Yahoo | Bing | Markdown
~~~

_Result:_

> engine|Language|Markup
> --------|------------|---------
> Google | Python | HTML
> Bing | JavaScript | Css
> Yahoo | Bing | Markdown

## Codeblock
Codeblock means sparate the code by box. Like write JavaScript inside the markdown in that case use codeblock. 

~~~markdown
    ~~~
     let first = 'Hello ';
     let secound = 'Word!';
     console.log(first+secound);
     ~~~
~~~

_Result:_
~~~
    let first = 'Hello ';
    let secound = 'World!';
    console.log(first+secound);
~~~
<br>
github flaver code black have extra feature. Spafify the language of code block.Example: 

~~~markdown
    ~~~javascript
    let first = 'Hello ';
    let secound = 'World!';
    console.log(first+secound);
    ~~~
~~~

_result:_

~~~javascript
    let first = 'Hello ';
    let secound = 'World!';
    console.log(first+seoound);
~~~

_HTML Example_

~~~markdown
    ~~~html
        <body>
            <h1>This is html heading</h1>
        </body>
    ~~~
~~~

_Result:_

~~~html
    <body>
        <h1>This is html heading</h1>
    </body>
~~~

## Collapsible
create collapsible in markdown language like html language

~~~markdown
    <details>
        <summary>JavaScript</summary>
        JavaScript is prototype based Language
        -------------------------------------
        Now Mordern world JavaScript use every here.But most use case is web.
    </details>
~~~

_Result:_

> <details>
>   <summary>JavaScript</summary>
>
>   JavaScript is prototype based Language
>   ============================
> Now Mordern world JavaScript use every here.But most use case is web.
> </details>

## Emoji

Use emoji in markdown language just need two colon and between the colon name of the emoji.

~~~markdown
    1. :blush:
    2. :rage:
    3. :confused:
~~~

_Result:_

> 1. :blush:
> 2. :rage:
> 3. :confused:

## Misc
Use keyboard key in markdown language is easy to write. In that case use `<kbd></kbd>` tag

~~~markdown
To Copy: <kbd>ctrl</kbd>+<kbd>c</kbd>
~~~

_Result:_

> To Copy: <kbd>ctrl</kbd> + <kbd>c</kbd>

## Badge

Go to [Shields](https://www.shields.io/ "Shields") site and create badge and copy the hyper link first. Then do below think like create image.

~~~markdown
![Badge](https://img.shields.io/badge/Md%20Tazri-Github-red 'This is Badge')
~~~

_Result:_

>![Badge](https://img.shields.io/badge/Md%20Tazri-Github-red 'This is Badge')

## Escape

If need to escape charecter just use \ black slash like programming langauge.

~~~markdown
\1. This is not list
\* This is not unorder list
\\* This is backslash and *
~~~

_Result:_

    \1. This is not list
    \* This is not unorder list
    \* This is backslash and *

## Comment

In markdown language write comment is very easy.

~~~markdown
[comment]: <> (This is comment)
[//]: <> (This is another comment)
[//]: <#> (This is the another comment which is support all version of markdown language.) 
~~~

_Result:_

>What are you think ? You see the comment as a result where comment can not show? :blush:

## End
Now I complate learn basic level markdown language syntax.:blush: