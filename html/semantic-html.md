# Semantic html

Semantic HTML is about using specific HTML tags to give meaning to the content on a webpage, rather than just focusing on how it looks. This is important for a few reasons:

1. **Helps Search Engines:** It makes it easier for search engines to understand the content and structure of your website, which can improve your site's visibility in search results.

2. **Accessibility:** It makes your website more accessible to people who use assistive technologies, helping them navigate and understand your content.

3. **Code Readability:** It makes your code easier to read and maintain because the purpose of each HTML element is clear.

Here are some common semantic HTML tags and how they're used:

- `<header>`: Marks the top section of a webpage, including the title, logo, and navigation links.

- `<nav>`: Marks a section specifically designed for navigation links.

- `<main>`: Marks the main content area of a webpage.

- `<article>`: Represents standalone content, like a blog post or news article.

- `<aside>`: Marks content related to the main content but not an integral part of it, like advertisements.

- `<section>`: Marks thematically grouped sections on a webpage.

- `<footer>`: Marks the bottom section of a webpage, including copyright information and contact details.

- `<details>` and `<summary>`: Used for collapsible sections of content.

- `<figure>` and `<figcaption>`: Used for self-contained content with a caption or description.

- `<mark>`: Marks highlighted text, like search results.

- `<time>`: Marks up a date or time.

- `<progress>`: Marks up a progress bar.

On the other hand, `<div>` and `<span>` are not semantic tags. They are generic tags used for grouping content but don't provide any specific meaning. They should be used only when no other option is available.

So, in summary, semantic HTML helps make websites more accessible and understandable by using specific tags to convey meaning.

### Examples
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Semantic HTML Example</title>
</head>
<body>

    <header>
        <h1>My Website</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section>
            <h2>Welcome to My Website!</h2>
            <p>This is the main content of my webpage. Feel free to explore and learn more about us.</p>
        </section>

        <article>
            <h3>Latest News</h3>
            <p>Exciting things are happening! Stay tuned for updates.</p>
        </article>

        <aside>
            <h3>Quick Links</h3>
            <ul>
                <li><a href="#services">Our Services</a></li>
                <li><a href="#team">Meet the Team</a></li>
            </ul>
        </aside>
    </main>

    <footer>
        <p>&copy; 2024 My Website. All rights reserved.</p>
    </footer>

</body>
</html>

```