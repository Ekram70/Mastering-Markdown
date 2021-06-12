# Mastering Markdown
A note for Markdown writing. Helpful for beginners like me. All the topic are covered in a sequential order.

## Table Of Contents

1. [Headings](#heading)
2. [Paragraph](#paragraph)
3. [Formatting Text](#formatting)
4. [Blockquotes](#blockquotes)
5. [List (Ordered & Unordered)](#list)
6. [Links - andchor](#link)
7. [Images- link](#images)
8. [Table Github](#table)
9. [Code Block](#code)
10. [Table of content](#content)
11. [Other](#other)

<br>

<a name="heading"></a>
### Headings

```md
# Heading 01
## Heading 02
Heading 01
==========
Heading 02
----------
### Heading 03
#### Heading 04
##### Heading 05
###### Heading 06
```

# Heading 01
## Heading 02
Heading 01
==========
Heading 02
----------
### Heading 03
#### Heading 04
##### Heading 05
###### Heading 06

<br>

<a name="paragraph"></a>
### Paragraphs

```html
Markdown is a lightweight and easy-to-use syntax
for styling all forms of writing on the GitHub platform.
```

Markdown is a lightweight and easy-to-use syntax <br>
for styling all forms of writing on the GitHub platform.

```html
<p align="center">
Markdown is a lightweight and easy-to-use syntax 
for styling all forms of writing on the GitHub platform.
</p>
```
<p align="center">
Markdown is a lightweight and easy-to-use syntax 
for styling all forms of writing on the GitHub platform.
</p>

<br>

        This is a special block

Tab creates a special block

<br>

<a name="formatting"></a>
### Formatting Text

```txt
**This is blod** <br>
__This is bold__ <br>
*This is italic* <br>
_This is italic* <br>
__This *is* mix__

~~Wor__king__~~ <br>
~~Wor_king_~~ <br>
~~Wor___king___~~ <br>
Wor**king** <br>
Wor*king* <br>
Wor***king*** <br>

***Bold Italic*** <br>
___Bold Italic___ <br>
__*Bold Italic*__ <br>
**_Bold Italic_** <br>


~~This is wrong~~
```

**This is blod** <br>
__This is bold__ <br>
*This is italic* <br>
_This is italic* <br>
__This *is* mix__

~~Wor__king__~~ <br>
~~Wor_king_~~ <br>
~~Wor___king___~~ <br>
Wor**king** <br>
Wor*king* <br>
Wor***king*** <br>

***Bold Italic*** <br>
___Bold Italic___ <br>
__*Bold Italic*__ <br>
**_Bold Italic_** <br>


~~This is wrong~~

<br>

<a name="blockquotes"></a>
### Blockqoutes

```txt
> This is a special blockquote
> This is a special blockquote

> This is a special blockquote
> 
> This is a special blockquote
> This is a special blockquote
>> This is a special blockquote
>>> This is a special blockquote

> **This is a** special *blockquote*
```

> This is a special blockquote
> This is a special blockquote

> This is a special blockquote
> 
> This is a special blockquote
> This is a special blockquote
>> This is a special blockquote
>>> This is a special blockquote

> **This is a** special *blockquote*

<br>

<a name="list"></a>
### List - Ordered & Unordered

```md
* Item 1
* Item 2
  - Item 2a
  - Item 2b
    + Item 2b1
    + Item 2b2

1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b
```


* Item 1
* Item 2
  - Item 2a
  - Item 2b
    + Item 2b1
    + Item 2b2

1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b

<br>

<a name="link"></a>
### Link - Anchor

```md
[Google](http://google.com) <br>
[Google](http://google.com "Google") <br>

<http://google.com> <br>
<ekramullah70@gmail.com> <br>

[Google][1] is a serach engine. [click here][2] to send mail.

[1]: <http://google.com> "Google"
[2]: <ekramullah70@gmail.com>
```

[Google](http://google.com) <br>
[Google](http://google.com "Google") <br>

<http://google.com> <br>
<ekramullah70@gmail.com> <br>

[Google][1] is a serach engine. [click here][2] to send mail.

[1]: <http://google.com> "Google"
[2]: <ekramullah70@gmail.com>


<br>

<a name="images"></a>
### Images - Link

```md
![GitHub Logo](GitHub.png)

<p align="center">
<img src="GitHub.png" width="200px">
</p>

[![GitHub Logo](GitHub.png)](https://github.com "github logo")
```

![GitHub Logo](GitHub.png)

<p align="center">
<img src="GitHub.png" width="100px">
</p>

[![GitHub Logo](GitHub.png)](https://github.com "github logo")


<br>

<a name="table"></a>
### Table github



| Syntax | Desccription |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |



<br>

<a name="code"></a>
### Code block

```
    `<inline>` code can be used

    ```
    <body>
        <p>This is a paragraph</p>
    </body>
    ```

    ```html
    <body>
        <p>This is a paragraph</p>
    </body>
    ```
```
`<inline>` code can be used

```
<body>
    <p>This is a paragraph</p>
</body>
```

```html
<body>
    <p>This is a paragraph</p>
</body>
```


<br>

<a name="other"></a>
### Other 

#### Checkbox

```md
- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media
```

- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media

#### Emoji
```md
That is so funny! :joy:
```

That is so funny! :joy:

#### Auto Url Link

```md
http://www.example.com
```

http://www.example.com

#### Disabled Link

```md
`http://www.example.com`
```
`http://www.example.com`


### Table of content

```md
[Table of content](#content)
<a name="content"></a>
```

[Table of content](#content)
<a name="content"></a>

### Horizontal line

    -----------------
-----------------

    *********************
*********************

    ___________________
___________________

### Keybord Shortcut

```md
Press <kbd>ctrl</kbd>+<kbd>c</kbd> to copy
```

Press <kbd>ctrl</kbd>+<kbd>c</kbd> to copy

### Badges
```md
![shields.io](https://img.shields.io/badge/Ekram-Ullah-green)
```

![shields.io](https://img.shields.io/badge/Ekram-Ullah-green)

### Escaping characters

```md
\# This is not a heading
```
\# This is not a heading
