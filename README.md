# 17 Computer Science for JavaScript: Regex Tutorial

## My Task

My assignment this week is to create a tutorial that explains how a specific regular expression, or regex, functions by breaking down each part of the expression and describing what it does. I'll use the template provided in the starter code to create your walkthrough.

## User Story

```md
AS A web development student
I WANT a tutorial explaining a specific regex
SO THAT I can understand the search pattern the regex defines
```

## Acceptance Criteria

```md
GIVEN a regex tutorial
WHEN I open the tutorial
THEN I see a descriptive title and introductory paragraph explaining the purpose of the tutorial, a summary describing the regex featured in the tutorial, a table of contents linking to different sections that break down each component of the regex and explain what it does, and a section about the author with a link to the author’s GitHub profile
WHEN I click on the links in the table of contents
THEN I am taken to the corresponding sections of the tutorial
WHEN I read through each section of the tutorial
THEN I find a detailed explanation of what a specific component of the regex does
WHEN I reach the end of the tutorial
THEN I find a section about the author and a link to the author’s GitHub profile
```

## What Is a Regex?

A **regex**, which is short for **regular expression**, is a sequence of characters that defines a specific search pattern. When included in code or search algorithms, regular expressions can be used to find certain patterns of characters within a string, or to find and replace a character or sequence of characters within a string. They are also frequently used to validate input.

For example, the following regular expression can be used to verify that user input is a valid email address:

`/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`

Each component of this regex has a unique responsibility to make sure that a user enters an email address that begins with an unspecified number of characters preceding the `@` symbol, followed by a domain.

Once I have a better understanding of what these different parts of a regular expression do, I’ll need to explain what they do for a specific regex.

## Getting Started

Instead of creating a repository, I’ll publish a GitHub gist. GitHub describes a **gist** as a simple way to share code snippets with others. It’s also an ideal way to demonstrate a technique, teach a principle, or show off a solution. It functions just like a repository, and I’ll use Markdown to create it, just as I do with my READMEs. Gists can include code, images, links, and anything else I can include in a README.

After I’ve downloaded the starter code, learnt [how to create a gist](https://help.github.com/en/github/writing-on-github/creating-gists), I could also watch this [video on how to use gists](https://www.youtube.com/watch?v=wc2NlcWjQHw) for better understanding.

## Note

- [The URL of the GitHub gist for Regex Tutorial.](https://gist.github.com/BadrulBorhanudin/a5e66809e6d16b174dc43c9f5817b6be)
