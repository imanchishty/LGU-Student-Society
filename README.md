LGU Student Society - Web Technologies Assignment #2

# Project Overview

This project is a three-page website for the Lahore Garrison University (LGU) Student Society. It fulfills all requirements for Assignment #2, utilizing semantic HTML, multimedia elements, HTML5 forms, and three different CSS implementation methods.

# Technical Explanations

CSS (Cascading Style Sheets) dictates the visual presentation of an HTML document. Its main benefit is separating the content's structure from its design, making the code much easier to maintain, ensuring a consistent look across the website, and reducing file duplication.

# CSS Rule Breakdown

In my style.css file, I used the rule: .btn-submit { background-color: #b76e79; }

Selector: .btn-submit (targets the submit button)

Property: background-color (what is being changed)

Value: #b76e79 (the specific rose-gold color applied)

# Three Methods of CSS Used

Inline CSS: Used exclusively on index.html via the style attribute directly inside HTML tags.

Embedded CSS: Used on information.html via a <style> block in the document's <head>.

External CSS: Used on registration.html by linking to style.css, which is the best practice for styling multiple pages.

# CSS Evolution

As required by the assignment rubric: CSS1 introduced basic fonts and colors. CSS2/2.1 added advanced positioning and media types. Modern modular CSS (CSS3) split the language into independent modules, bringing features like Flexbox, Grid, and advanced form styling which I used in my project.

# Browser Testing

I tested this site on Google Chrome and Mozilla Firefox. Browser support is critical because different browsers use different rendering engines (like Blink or Gecko). This means they might interpret padding, margins, or HTML5 form validation slightly differently, so testing ensures all users get a consistent experience.

# HTML Element Examples

Semantic HTML: The <article> tag on my Information page clearly defines a self-contained section about the Spring Expo.

Non-Semantic HTML: The <div> tags on my Registration page simply group form inputs together for styling, without describing what the content actually is.