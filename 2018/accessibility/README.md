# Web Accessibility

> An introduction to web accessibility.

## What does this mean?

Web accessibility is the idea of creating websites and web applications that can be used by anyone, even people that have no vision, hearing, or other physical ability.

> people with disabilities can perceive, understand, navigate, and interact with the Web, and that they can contribute to the Web.

— W3C

For example, you can make a website that someone can navigate using only the keyboard. This means they can access all parts of the website, including menus, with the arrow keys and enter key. Another commonly used key is tab, which brings the focus to the next element on the screen. Shift + Tab to go back.

## Why is it important?

You can spread the website's message, product, or service to a greater audience.

- More people can benefit
- More people can access valuable information
- Increased revenues for business
- Happier customers

In some organizations, it is required by law.

## The HTML standard

The people who work on the standard have already implemented best practices in HTML to ensure accessibility. You just need to follow them.

https://www.w3.org/WAI/WCAG20/quickref/

## Using the right elements

You may have heard the term "Semantic HTML".

https://www.w3schools.com/html/html5_semantic_elements.asp

> Semantics is the study of the meanings of words and phrases in a language.

> Semantic elements = elements with a meaning.

New elements in HTML5 to take advantage of:

- <article>
- <aside>
- <details>
- <figcaption>
- <figure>
- <footer>
- <header>
- <main>
- <mark>
- <nav>
- <section>
- <summary>
- <time>

## Attributes

`title` - https://developer.paciellogroup.com/blog/2010/11/using-the-html-title-attribute/

`alt` - https://en.wikipedia.org/wiki/Alt_attribute

`role` - https://stackoverflow.com/questions/10403138/what-is-the-purpose-of-the-role-attribute-in-html#18664038

## Connection speed

Accessibility also means that people with slower connections can access your website.

There are options in the developer tools to simulate various connection speeds. Known as "throttling".

Global average is only *5.6 Mbps*. Remember that if your site is hosted in another country, the higher latency makes the website or application appear to be even slower.

Ask yourself, does the content I am adding add value to the site?

There are a number of ways to improve website speed:

- Caching
- Fewer requests
- CDN
- Host on server closest to large majority of users
- Optimize PNG images
- Minify files sent to client
- Server compression

https://tools.pingdom.com/

## Progressive enhancement

Start with HTML first, then apply styles, and add JavaScript as necessary.

Load JavaScript at the end of the file.

This way, the most important content will appear first.

## Should websites work without JS/CSS?

It depends.

https://alistapart.com/article/understandingprogressiveenhancement

Angular applications, for example, are completely JavaScript.

It might not be worth the effort to maintain a second version with only server side processing.

It would be best to display *something*, if only a message that you need JavaScript for the site to work. Don't leave users looking at a blank screen.

## Screen readers

Modern operating systems have this built in, so you can try it on your websites. See how easy it is to navigate the website using only what the screen reader tells you.

This is where semantic layout of HTML elements, `alt` attributes, and other accessibility features will be helpful.

## References

https://www.w3.org/WAI/intro/accessibility.php

