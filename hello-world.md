---
author: Joe Smith
avatar_url: https://github.com/
header_pic_url: https://github.com/crevizzle/blog/raw/main/web-dev.jpg
link_preview_url: https://github.com/crevizzle/blog/raw/main/web-dev.jpg
title: Web Development Basics
subtitle: An example article for the Yemi blogging platform
published: 1/1/2021
updated: 1/5/2021
seo_canonical: https://yemi.blog
seo_description: fake description
seo_title: faker title
---
## What is web development?

According to [wikipedia](https://en.wikipedia.org/wiki/Web_development), web development is

> ...the work involved in developing a Web site for the Internet (World Wide Web) or an intranet (a private network).

### ^^^^^ paid features of Yemi allow you to theme your site. Here, we use your secondary theme color for a block quote

Here is how we sum up web development: It's the processes, languages and tools we use to build websites and webapps.

## Tell me more

Some people refer to web development as webdev.

There are three main "languages" in webdev today:

1) HTML
2) CSS
3) Javascript

There are others out there, but these are the most well known.

## HTML

HTML stands for HyperText Markup Language. Simply put, it defines the structure of a website. HTML is created by defining "elements"; which are the building blocks of webpages.

## CSS

CSS stands for Cascading Style Sheets. CSS is responsible for the presentation - or look - of webpages. Think color, size, etc.

CSS can also add reactivity to your site. When you hover over a link or button, the colors or other properties of it may change.

## Javascript (JS)

Javascript helps bring your site to life, so-to-speak. It enables your site to function, be dynamic and also reactive.

When you're shopping online and add something to your cart, it's most likely javascript doing part of the work. If you increase the quantity of how many things you're buying, that's javascript updating the number.

### [Back to Yemi](https://yemi.blog/#login)

## Can you show me an example of this code?

```
<html>
  <head>
    <meta charset="utf-8">
    <meta content="width=device-width,initial-scale=1" name="viewport">
    <title>Web Development Basics</title>
  </head>
  <body>
    <nav class="nav-bar">
      <div>
        Logo Here
      </div>
    </nav>
    <main>
      <div>
        Content Here
      </div>
    </main>
    <footer>
      <p>Copyright &copy; - <span id="copyright"></span></p>
    </footer>
  </body>
  <script>
    const copyright = document.getElementById('copyright');
    const copyYear = new Date().getFullYear();
    copyright.textContent = copyYear;
  </script>
</html>
```

### ^^^^^ Add some codeblocks! We use highlight.js!

## What others think

> Web development is the most fun career path I've ever taken!

## How do I get started?

### Start by reading these

Mozilla's [MDN](https://developer.mozilla.org/en-US/docs/Learn) resources are excellent!

[web.dev](https://web.dev/learn/) is also a great resource for learning web development!

### Start by watching

Here are some great free courses on YouTube

[HTML](https://youtu.be/UB1O30fR-EE)

[CSS](https://youtu.be/yfoY53QXEnI)

[Javascript](https://youtu.be/hdI2bqOjy3c)


Web development isn't as complicated and scary as a lot of people think. You can do this!

### [Back to Yemi](https://yemi.blog/#login)
