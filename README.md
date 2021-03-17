# Code Refactors

## Improving HTML accessability and consolidating CSS

The goal of this exercise was to improve the accessabilty of a given webpage to increase readability for Search Engine Optimization and for those with disabilities or who are using a screen reader.

## Changes to the index.html

The given website made extensive use of the <div> tag for multiple elements, which provides little information to search engines and screen readers. Multiple changes were made across the page to eliminate the use of <div> tags and to replace them with the correct semantic elements including:

<header>
<main>
<section>
<aside>
<footer>

Images were also provided with <alt> tags to improve accessability.

## Changes to the style.css

The given style sheet had multiple places in which elements were styled with similar code, consolidated the style sheet to eliminate excess code that provided the same function.

### See individual comments within the files for exact changes


![The Horiseon webpage includes a navigation bar, a header image, and cards with text and images at the bottom of the page.](./assets/images/website-screenshot.png)
