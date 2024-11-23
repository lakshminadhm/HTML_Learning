# HTML Document Structure

The structure of an HTML document is essential to understanding how a webpage is organized and interpreted by web browsers. Every HTML file follows a basic structure that includes key elements defining its content and behavior.

## Overview of the Document Structure

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document Title</title>
</head>
<body>
    <h1>Welcome to My Webpage</h1>
    <p>This is an example paragraph.</p>
</body>
</html>
```

## Breaking Down the Structure
### 1. DOCTYPE Declaration
```html
<!DOCTYPE html>
```
- The **`<!DOCTYPE html>`** declaration specifies the document type and version of HTML being used.
- It ensures the browser renders the page correctly.
- Modern HTML documents use `<!DOCTYPE html>` for HTML5.
- More about DOCTYPE - [Evolution and Details of DOCTYPE in HTML](./DOCTYPE/README.md)

### 2. Root Element: `<html>`
```html
<html lang="en">
```
- The `<html>` element is the root of the HTML document.
- All other elements are nested inside `<html>`.
- **Attributes**:
  - `lang="en"` specifies the document's language (English in this case). This is important for accessibility and search engines.
- More about `<html>`: [`<html>` (Root Element)](./root-element/README.md)

#### 3. Head Section: `<head>`
```html
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document Title</title>
</head>
```
- Contains **metadata** and other information for the document.
- This information is not directly visible on the webpage but is critical for its behavior and SEO.
- **Key Elements in `<head>`:**
	- `<meta charset="UTF-8">`: Specifies character encoding. UTF-8 supports most languages and symbols.
	- `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: Ensures responsive design, making pages mobile-friendly.
	- `<title>`: Defines the text shown in the browser tab or window title.
- Optional elements:
  - `<link>`: Links external resources like stylesheets.
  - `<style>`: Contains internal CSS.
  - `<script>`: Embeds JavaScript code.
- More about `<head>` : [Understanding the `<head>` Section](./head-element/README.md)


### 4. Body Section: `<body>`
```html
<body>
    <h1>Welcome to My Webpage</h1>
    <p>This is an example paragraph.</p>
</body>
```
- Contains all the visible content of the webpage.
- Elements within `<body>` include:
  - **Headings**: `<h1>` to `<h6>` for titles and subheadings.
  - **Paragraphs**: `<p>` for blocks of text.
  - **Images**: `<img>` for pictures.
  - **Links**: `<a>` for hyperlinks.
  - **Lists**: `<ul>` (unordered) and `<ol>` (ordered) for lists.
- More about `<body>` : [Understanding the `<body>` Section in HTML](./body-section/README.md)

## Detailed Element Table

| **Element**    | **Description**                                                                 |
|-----------------|---------------------------------------------------------------------------------|
| `<!DOCTYPE>`   | Declares the document type as HTML5.                                            |
| `<html>`       | Root element enclosing all content.                                             |
| `<head>`       | Contains metadata, links, and other non-visible information.                   |
| `<meta>`       | Provides metadata like encoding, viewport, and document descriptions.          |
| `<title>`      | Displays the page title in the browser tab.                                     |
| `<body>`       | Contains visible content displayed to users.                                   |
| `<h1>` to `<h6>` | Headings for content, `<h1>` being the largest and `<h6>` the smallest.        |
| `<p>`          | Paragraphs for text content.                                                   |
| `<img>`        | Displays images with attributes like `src` and `alt`.                          |
| `<a>`          | Creates hyperlinks to other pages or resources.                                |

---

## Example of a Complete Document
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My First Webpage</title>
</head>
<body>
    <h1>Welcome to HTML!</h1>
    <p>This is a paragraph explaining the basic structure of an HTML document.</p>
    <ul>
        <li>First item in an unordered list</li>
        <li>Second item in an unordered list</li>
    </ul>
    <a href="https://www.example.com" target="_blank">Visit Example</a>
</body>
</html>
```

## Key Notes
1. **Hierarchy Matters**: The structure follows a parent-child relationship, starting with `<html>` as the root.
2. **Well-Formatted Code**: Proper indentation improves readability.
3. **Attribute Usage**: Attributes like `lang`, `charset`, and `href` provide additional context and functionality.

## Exercise
1. Create an HTML file named `document_structure.html`.
2. Build a basic HTML document with:
   - A heading (`<h1>`).
   - A paragraph (`<p>`).
   - An ordered list (`<ol>`).
   - A link (`<a>`).
3. Save the file and open it in a browser.

Example output:
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>HTML Structure Exercise</title>
</head>
<body>
    <h1>HTML Document Structure</h1>
    <p>This exercise demonstrates the basic structure of an HTML file.</p>
    <ol>
        <li>Step 1: Write HTML code</li>
        <li>Step 2: Save with .html extension</li>
        <li>Step 3: Open in a browser</li>
    </ol>
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML" target="_blank">Learn more about HTML</a>
</body>
</html>
```