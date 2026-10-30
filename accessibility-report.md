# Accessibility Audit Report

**Project:** Personal Portfolio Website  
**Page Audited:** index.html  
**Developer:** Stacy Otieno  
**Date:** 30 October 2026

## 1. Issues Found

During the accessibility audit, the following issues were identified:

1. **Image alternative text:** The image had a short alt description ("Stacy") that could be more descriptive.
2. **Heading hierarchy:** The page jumped from an h1 heading directly to an h3 heading.
3. **Descriptive links:** The email link used "Stacy" instead of a more meaningful description.
4. **HTML language:** The page already included `lang="en"`, so no correction was necessary.
5. **Form labels:** The homepage did not contain form inputs, so this requirement was not applicable.

## 2. Fixes Implemented

The following improvements were made:

- Updated image alternative text to "Photograph of Stacy Otieno".
- Corrected heading hierarchy by introducing appropriate h2 headings.
- Changed the email link text to "Email Stacy Otieno".
- Retained the `lang="en"` attribute.
- Organized content using semantic HTML elements such as `<header>`, `<main>`, and `<section>`.
- Separated paragraphs using `<p>` elements instead of unnecessary line breaks.

## 3. Accessibility Testing Tools

The following tools were used to evaluate the website:

- Google Chrome Lighthouse
- WAVE Web Accessibility Evaluation Tool

## 4. Lighthouse Accessibility Score

**Final Accessibility Score: 89/100**

The Lighthouse accessibility audit was performed after implementing the corrections.

## 5. Conclusion

The accessibility audit helped identify areas where the website could be improved to make it more accessible and user-friendly.

The improvements included better image descriptions, proper heading structure, descriptive links, and semantic HTML.

The website was also checked using Lighthouse and WAVE to identify additional accessibility issues.

Overall, the audit improved my understanding of accessible web development and the importance of creating websites that can be used by everyone.
