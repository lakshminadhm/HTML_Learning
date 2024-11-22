
# Getting Started with HTML

## 1. Creating Your First HTML File

### Step 1: Open a Text Editor

To write HTML code, you need a text editor. Here are some options:
-   **Built-in Editors**:
    -   **Windows**: Notepad or Notepad++
    -   **Mac**: TextEdit (switch to plain text mode)
-   **Recommended Editors**:
    -   [**Visual Studio Code (VS Code)**](https://code.visualstudio.com/) - Lightweight and powerful.
    -   [**Sublime Text**](https://www.sublimetext.com/) - Fast and elegant.

### Step 2: Write Your First HTML Code

1.  Open your text editor and write the following code:
	```html
	<!DOCTYPE html>
	<html lang="en">
	<head>
	    <meta charset="UTF-8">
	    <meta name="viewport" content="width=device-width, initial-scale=1.0">
	    <title>My First HTML Page</title>
	</head>
	<body>
	    <h1>Welcome to My First HTML Page!</h1>
	    <p>This is a simple paragraph of text.</p>
	</body>
	</html>` 
	```
2.  Save the file:
    -   Use the **`.html`** extension.
    -   Example: `index.html`.

## 2. Choosing an IDE or Editor

### Why Use a Code Editor?

While basic editors like Notepad  and TextEdit work but code editors and IDEs offer:
-   Syntax highlighting.
-   Auto-completion.
-   Integrated terminal for quick testing.

### Recommended Tools

1.  **Visual Studio Code (VS Code)**
    -   Download: [VS Code](https://code.visualstudio.com/)
    -   Extensions for HTML:
        -   HTML Snippets
        -   Live Server (for previewing your HTML in real-time)
2.  **Sublime Text**
    -   Lightweight and efficient.
    -   Great for small projects.
3.  **Web-Based Editors** _(No Installation Required)_:
    -   [CodePen](https://codepen.io/): Ideal for testing and sharing code snippets.
    -   [JSFiddle](https://jsfiddle.net/): Quick prototyping for HTML, CSS, and JavaScript.
    - A lot more exists.

## 3. **Running Your HTML File**

### Method 1: Open Directly in a Browser

1.  Save your `index.html` file.
2.  Double-click the file.
3.  It will open in your default web browser (Chrome, Firefox, etc.).

### Method 2: Use a Code Editor with Live Preview

1.  Install the **Live Server** extension (in VS Code).
2.  Open your HTML file in VS Code.
3.  Right-click the file and select `Open with Live Server`.
4.  Your browser will display the file, and any changes you save will reflect instantly.

### Method 3: Use an Online Editor

1.  Open [CodePen](https://codepen.io/) or [JSFiddle](https://jsfiddle.net/).
2.  Paste your HTML code into the editor.
3.  The browser will display the result immediately.


## 4. **Testing and Modifying Your HTML**

-   Edit your file to add new content or fix errors.
-   Save the changes and refresh the browser to see the updates.

# Example Exercise

1.  Create an HTML file named `practice.html`.
2.  Add the following:
    -   A heading (`<h1>`).
    -   A paragraph (`<p>`).
    -   An image (`<img>`).
	  ```html
	<!DOCTYPE html>
	<html lang="en">
	<head>
	    <title>Practice File</title>
	</head>
	<body>
	    <h1>This is a Practice Page</h1>
	    <p>Hello, world! Welcome to my webpage.</p>
	    <img src="example.jpg" alt="Example Image">
	</body>
	</html>
	```
3.  Save the file and open it in a browser.
