# 📘 Assignment: HTML5 + Accessibility & SEO Basics

## Overview

This assignment will help you solidify your understanding of modern HTML5 structure while applying foundational concepts of web accessibility and search engine optimization (SEO). You’ll create a simple, semantically correct web page that prioritizes both human and machine readability—two pillars of great web design.

## Objective

Build a basic web page using HTML5 semantic tags, applying accessibility best practices and beginner-friendly SEO principles. Your final output should demonstrate a well-structured layout that supports screen readers and is optimized for discoverability.

## Guidelines

Use only HTML5. No CSS or JavaScript is required at this stage. Focus on using meaningful semantic elements to structure your page. Avoid using `<div>` or `<span>` unless absolutely necessary. Ensure your page has clearly defined sections such as a header, navigation, main content, and a footer.

Incorporate accessibility by using proper HTML5 landmarks and attributes that improve navigation for assistive technologies. Your HTML should reflect thoughtful planning of hierarchy and readability, both for users and search engines.

For SEO, emphasize the use of heading tags in the correct order, provide descriptive text, and ensure your content is both human-readable and crawler-friendly. Consider how a search engine would interpret your page in terms of structure and content clarity.

## Deliverables

A single HTML file named `index.html`. It should include:

* A semantic structure using appropriate HTML5 elements.
* Clear headings in a logical hierarchy.
* Accessibility enhancements using proper tags and attributes.
* SEO-friendly metadata and content.

## Tips

* Use HTML5 semantic tags appropriately.
* Organize content with accessibility in mind.
* Apply basic on-page SEO techniques.
* Follow clean, readable HTML code structure.

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="description" content="A beginner-friendly HTML5 page built with love, learning, and semantic tags." />
  <meta name="keywords" content="HTML5, student project, accessibility, SEO, web dev basics" />
  <meta name="author" content="Emmanuel Katama" />
  <title>My First Semantic Web Page 🎓</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <header role="banner">
    <h1>Hello World! 👋</h1>
    <nav role="navigation" aria-label="Main Menu">
      <ul>
        <li><a href="#about">About Me</a></li>
        <li><a href="#articles">My Articles</a></li>
        <li><a href="#contact">Say Hi</a></li>
      </ul>
    </nav>
  </header>

  <main role="main">
    <section id="about" aria-labelledby="about-heading">
      <h2 id="about-heading">About This Project</h2>
      <p>Hey there! I'm learning how to build web pages using HTML5. This one uses semantic tags, accessibility tricks, and a sprinkle of SEO magic.</p>
    </section>

    <section id="articles" aria-labelledby="articles-heading">
      <h2 id="articles-heading">Cool Stuff I Wrote ✍️</h2>
      <article>
        <h3>Why Semantic Tags Are Like Good Friends</h3>
        <p>They help browsers and screen readers understand your content better—like giving directions to a lost tourist!</p>
      </article>
      <article>
        <h3>Accessibility 101: Making Everyone Feel Welcome</h3>
        <p>From alt text to ARIA labels, it's all about making sure no one’s left out of the party.</p>
      </article>
    </section>
  </main>

  <aside role="complementary" aria-label="Sidebar Tips">
    <h2>Quick Tips for Fellow Learners 💡</h2>
    <ul>
      <li>Use tags like `<main>`, `<section>`, and `<article>` to organize your content</li>
      <li>Write a clear `<title>` and add helpful `<meta>` info</li>
      <li>Use ARIA labels to guide screen readers</li>
    </ul>
  </aside>

  <footer role="contentinfo">
    <p>Made with 💻 & ☕ by Emmanuel Katama. &copy; 2025</p>
  </footer>
</body>
</html>
