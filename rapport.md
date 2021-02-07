---
title: "document title"
author: 
    - author name
date: 01-01-1900
headertext: "header text"
footertext: "footer text"
include-before:
    - '\renewcommand{\contentsname}{Table of contents}'
    - '\let\oldtoc\tableofcontents'
    - '\renewcommand{\tableofcontents}{\oldtoc\newpage}'
    - '`\newpage{}`{=latex}'
header-includes: |
    \usepackage{fancyhdr}
    \pagestyle{fancy}
    \fancyhead[R]{author name}
    \fancyhead[L]{header text}
    \fancyfoot[L]{footer text}
---

\newpage

# Introduction

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

# Code

```html
<html>
    <head>
        <meta charset="utf-8" />
        <title>test</title>
    <head>
    <body>
        <h1>Title</h1>
        <p>Some content</p>
    </body>
</html>

```

# Section level 1

Lorem ipsum dolor sit amet.

## Section level 2

Lorem ipsum dolor sit amet

## Section level 2

Lorem ipsum dolor sit amet

# Math

\begin{align*}
\sum_{k = 1}^{\infty} 2^k
\end{align*}

# Bullet list

* item 1
* item 2
* item 3 

# Image

Image from [dummyimage.com](https://dummyimage.com/)

![](img/dummy.png)
