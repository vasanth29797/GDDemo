# Emphasis

**bold**
*italic*
~~strikethrough~~

# Links

[Link to google!](http://google.com)

## Relative link

[abc.txt](/abc.txt/)

# Lists

## Unordered (with asteriks)

* game of thrones
  * stark
  * targaryen
  * lannister
* breaking bad
  * walter white

## Unordered (with dashes)  

Bullet points with dashes
- google
  - gmail
  - drive
    - upload
    - download

## Ordered

1. Item 1
1. Item 2
1. Item 3
   1. Item 3a (with 3 spaces indentation)
   1. Item 3b

# Headers

# `<h1>`
## `<h2>`
###### `<h6>`

# Blockquotes

> quote
> by vasanth

# Inline codes

## Inline single line code
`int a = 1;`

## Inline code block with 4 spaces indentation
    int a = 1;
    if (a == 1) {
      printf("one");
    } else {
      printf("can't guess.");
    }

## Inline code block also with 3 backticks - code fencing
```
int a = 1;
if (a == 1) {
printf("one");
} else {
printf("can't guess.");
}
```

## Above + syntax highlighting
```c
int a = 1;
if (a == 1) {
printf("one");
} else {
printf("can't guess.");
}
```
# Usernames \@mention

@github/support

# Ignorance md formatting (with \\)

\*bold\*

# Task lists

- [x] checked
- [ ] unchecked

# Emoji

:camel:
:boom:
:+1:

# tables

th1 | th2
--- | ---
td1 | td2
td1 | td2

# Line break

## with 2 spaces indentation

hello  
world

## with `<br\>`

hello<br/> 
world

## with `\`

hello  
world

# Images

## Inline-style

![meme](https://media.giphy.com/media/l3mZrofd8Q2SA1I1q/giphy.gif =100x100)

## Inline-style (with title text)

![meme](https://media.giphy.com/media/l3mZrofd8Q2SA1I1q/giphy.gif "title text")

## Reference-style (with a line break btw each line)

![meme][logo]

[logo]: https://media.giphy.com/media/l3mZrofd8Q2SA1I1q/giphy.gif "title text"

# Horizontal rules (use three or more)

hyphens
---
asteriks
***
underscores
___

# Using HTML

<p align="center">
  <b>Bold text</b>
  <br/>
  <a href="http://google.com">Google</a> |
  <a href="http://apple.com">Apple</a> |
  <a href="http://amazon.com">Amazon</a>
  <br/><br/>
  <img src="https://media.giphy.com/media/l3mZrofd8Q2SA1I1q/giphy.gif" alt="gif">
</p>