---
layout: post
title: Hello, World!
tags: [Personal, First Post]
categories: Blog
author: sidiq
excerpt_separator: <!--more-->
date: 2024-06-11
---

Hey there! 👋
<!--more-->
```javascript
console.log('Hello, World!');
```
\
I bet the words "Hello World" sound super familiar, right? When we first started learning to code, it was like the official welcome wagon and the first thing most tutorials threw at us. 😆

\
Honestly, I kind of dig the whole "Hello World" thing. It's like a warm hug that makes me want to dive deeper into the coding world. ✨  Speaking of diving in, this is my very first blog post, and I thought "Hello World" was a pretty fitting title, don't you think? 😄

\
Since this is my first post, I wanted to chat a bit about taking that first step. It's tough, I know. 😣 Especially for someone like me who tends to be a bit of a perfectionist. 😅I always feel like I need to research everything to death before I can actually do anything.

\
But when you take that too far, it's easy to get stuck in planning mode and never actually take action. It's like this weird illusion of being productive, but in reality, you're just wasting time. 😫

\
So, why is it so hard to take that first step? For me, it's the fear of failure and making mistakes. It feels like one wrong move and everything I've worked for will go up in smoke. 💥

\
But here's the thing: what's so bad about making mistakes? 🤔 What really happens when we mess up? Do we suddenly disappear? 👻 Nope! Most of the time, nobody even notices or cares. And even if it's a mistake that affects others, usually the worst that happens is you get a little scolding. 🤷‍♀️

\
So, what I'm trying to say is, planning is great, but too much planning can hold you back. Sometimes it's better to just learn by doing, make mistakes, and then use that feedback to get better. 💪

\
Okay, I think that's enough rambling for now. Just remember: "Just Do It" and good luck, friends! 🚀


# Headers
## Level 2
### Level 3
#### Level 4
##### Level 5
###### Level 6
 
# [Headers with links](http://localhost)
## [Level 2](http://localhost)
### [Level 3](http://localhost)
#### [Level 4](http://localhost)
##### [Level 5](http://localhost) 
###### [Level 6](http://localhost)

## Code highlight
Mode specific code highlighting themes. [Kramdown](https://kramdown.gettalong.org/) which is responsible for the color highlighting may be more limited than your IDE.

```python
#!/usr/bin/env python
"""
Test file for syntax
"""
# TODO: Use dark mode
from sys import os

def foo(bar): 
    try:
        print(bar)
    except NameError:
        print("Variable bar is not defined")


class Bar(object): 
    def __init__(self):
        foo(1)
        self.octal = '\04'
        self.text = """Example \t\n"""
    
    def __exit__(self, *args):
        print('exit\u1111\xFF')
        pass
    
    @staticmethod
    def example():
        assert (1.0 and 2L) or True
        return { "example": [(1,), (r'raw', u'unicode')]}
```

## Tables

| hex | dec | oct |
| -   | -   | -   |
| 0   | 0   | 0   |
| 5   | 5   | 5   |
| A   | 10  | 12  |
| F   | 16  | 20  |
| F5  | 21  | 25  |

## KaTeX

Some KaTeX diagrams to check in dark mode:

$$
\begin{CD}
A @>a>> B \\
@VbVV @AAcA \\
C @= D
\end{CD}
$$

$$\utilde{AB}$$

## Mermaid

<div class="mermaid">
flowchart TB
    c1-->a2
    subgraph one
    a1-->a2
    end
    subgraph two
    b1-->b2
    end
    subgraph three
    c1-->c2
    end
</div>
