1) What is the Shortcut Emmet Used to Create boilerplate of HTML?
Use this Emmet shortcut:
!
Then press Tab (or Enter in some editors).
It expands to a full HTML5 boilerplate.

2) What is DOCTYPE in Html?
DOCTYPE is a declaration at the top of an HTML file:
<!DOCTYPE html>
It tells the browser to render the page in standards mode (modern HTML5 rules), not quirks mode.

3) What is Void Element and Example for Void Elements?
A void element is an HTML element that does not have a closing tag and cannot contain content.
Examples:
- <img>
- <br>
- <hr>
- <input>
- <meta>
- <link>

4) What is Different Element and Attributes?
- Element: The HTML tag structure used to define content.
  Example: <p>Hello</p> is a paragraph element.
- Attribute: Extra information added inside the opening tag.
  Example: <img src="photo.jpg" alt="My photo">
  Here, src and alt are attributes.

5) What is Html Entries and Why is it need in HTML?
(Usually called HTML Entities.)
HTML entities are special codes used to display reserved/special characters in HTML.
Examples:
- &lt;  shows <
- &gt;  shows >
- &amp; shows &
- &copy; shows ©
Why needed:
- To display characters that HTML normally treats as markup.
- To show symbols safely and correctly in all browsers.

6) What are meta tag and why is it used
Meta tags provide metadata (information about the page) in the <head> section.
Common examples:
- <meta charset="UTF-8"> (text encoding)
- <meta name="viewport" content="width=device-width, initial-scale=1.0"> (responsive layout on mobile)
- <meta name="description" content="..."> (SEO summary)
Why used:
- Better browser behavior
- Mobile responsiveness
- SEO and social sharing support

7) what is the best way to add images in Website?
Best practice is to combine local optimized images + modern formats + responsive markup:
- Store important site images locally in your project/assets.
- Use modern formats: WebP/AVIF (with fallback if needed).
- Compress images to reduce load time.
- Use descriptive alt text for accessibility.
- Use responsive images (srcset/sizes) for different screen sizes.
- Use CDN when you need faster global delivery and caching for large/public assets.

In short: for most projects, use optimized local images for control and reliability, and use a CDN for performance at scale.