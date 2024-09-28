# -EMC-platform-Registration-
Here's a detailed explanation of the HTML code of EMC-platform-Registration

## Code Overview

The HTML document provided is structured into multiple sections, including a registration form for a fictional academy named "Error Makes Clever Academy," a table explaining full-stack development, and links to social media and external sites.

### HTML Document Structure

The HTML code uses the following main elements:

### Head Section

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>EMC</title>
</head>
<body>
```
- **`<!DOCTYPE html>`**: Specifies the document type as HTML5.
- **`<html lang="en">`**: Sets the language of the document to English.
- **`<head>`**: Contains the metadata of the webpage.
  - **`<title>EMC</title>`**: Sets the title of the webpage to "EMC," which appears in the browser tab.
- **`<body>`**: Starts the body section where all visible content is placed.

### Academy Introduction Section

```html
<center>
    <h1>Error Makes Clever Academy 🚀</h1>
    <h5>Training | Tech News | Freshers Guide</h5>
    <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit...</p>
</center>
<hr>
```
- **`<center>`**: Deprecated tag that centers the content.
  - **`<h1>`**: Displays the main heading "Error Makes Clever Academy 🚀".
  - **`<h5>`**: Displays a subheading with the text "Training | Tech News | Freshers Guide."
  - **`<p>`**: Contains a paragraph with placeholder text (`Lorem ipsum`), often used for temporary content.
- **`<hr>`**: Horizontal line separator, visually dividing sections of content.

### Registration Form Section

```html
<center>
    <h2>REGISTRATION FORM</h2>
    <form>
        <table>
            <tr>
                <td>Name:</td> <td><input type="text" placeholder="Enter your Name"></td>
            </tr>
            <tr>
                <td>Age:</td><td><input type="number" placeholder="Enter your Age"></td>
            </tr>
            <tr>
                <td>Gender:</td>
                <td>
                    <input type="radio" name="Gender">Male
                    <input type="radio" name="Gender">Female
                </td>
            </tr>
            <tr>
                <td>Email:</td> <td><input type="email" placeholder="Enter your Email"></td>
            </tr>
            <tr>
                <td>Select a Course:</td>
                <td>
                    <select>
                        <option>Full Stack Development</option>
                        <option> Python </option>
                        <option>HTML</option>
                    </select>
                </td> 
            </tr>
            <tr>
                <td> Upload your Resume</td>
                <td>
                    <input type="file">
                </td>
            </tr>
            <tr>
                <td><input type="reset"></td>
                <td><input type="submit"></td>
            </tr>
        </table>
    </form>
</center>
<hr>
```
- **`<center>`**: Centers the form content.
  - **`<h2>`**: Displays a subheading "REGISTRATION FORM."
  - **`<form>`**: Creates a form to accept user inputs.
    - **`<table>`**: Arranges form elements in a table layout.
      - **`<tr>`**: Represents a table row.
      - **`<td>`**: Represents a table cell for text and form inputs.
        - **Name Field**: Uses `<input type="text">` for entering the name.
        - **Age Field**: Uses `<input type="number">` for entering age.
        - **Gender Field**: Uses `<input type="radio">` for selecting gender.
        - **Email Field**: Uses `<input type="email">` for entering an email address.
        - **Course Selection**: Uses `<select>` dropdown to choose a course.
        - **Resume Upload**: Uses `<input type="file">` to upload a file.
        - **Reset and Submit Buttons**: `<input type="reset">` resets the form, and `<input type="submit">` submits the form.
  - **`<hr>`**: Another horizontal line separator to divide sections.

### Links to External Pages

```html
<center>
<a href="index.html">Home|</a> 
<a href="https://www.instagram.com/errormakesclever/?hl=en">Instagram|</a> 
<a href="http://www.youtube.com/@ErrorMakesClever">YouTube</a>
</center>
```
- **`<center>`**: Centers the links.
  - **`<a href="index.html">Home|</a>`**: Link to the homepage (`index.html`).
  - **`<a href="https://www.instagram.com/errormakesclever/?hl=en">Instagram|</a>`**: Link to the academy's Instagram page.
  - **`<a href="http://www.youtube.com/@ErrorMakesClever">YouTube</a>`**: Link to the academy's YouTube channel.

### Embedded YouTube Video

```html
<center>
    <iframe width="560" height="315" src="https://www.youtube.com/embed/FYErehuSuuw?si=2py9CCByDt7sJdUX" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</center>
```
- **`<center>`**: Centers the video content.
- **`<iframe>`**: Embeds a YouTube video with specified width and height. The video is identified using the URL `https://www.youtube.com/embed/FYErehuSuuw`.
- The attributes **`allow`** and **`allowfullscreen`** enable additional features like autoplay and full-screen mode for the video.

### Full Stack Development Information

```html
<h3>Let's Divide Full stack into 3 parts</h3>
<ul>
    <li>Frontend</li>
    <li>Backend</li>
    <li>Database</li>
</ul>

<h3>Technologies Used For Full Stack Development</h3>
<table border="1">
    <tr>
        <td>Frontend</td><td>Backend</td><td>Database</td>
    </tr>
    <tr>
        <td>HTML</td><td>Java</td><td>Mongo DB</td>
    </tr>
    <tr>
        <td>CSS</td><td>Python</td><td>MYSQL</td>
    </tr>
    <tr>
        <td>JavaScript</td><td>Node JS</td><td>AWS</td>
    </tr>
</table>
<hr>
```
- **`<h3>`**: Displays a subheading describing the division of full-stack development.
- **`<ul>`**: Creates an unordered list.
  - **`<li>`**: Lists items for frontend, backend, and database parts.
- **`<table>`**: Creates a table explaining technologies for each part of full-stack development.
  - The table is structured into three columns: Frontend, Backend, and Database.
  - Each row lists different technologies under these categories (e.g., HTML for Frontend, Java for Backend, etc.).

### Final Links

```html
<center>
<a href="register.html">Register for a Course|</a> 
<a href="https://www.instagram.com/errormakesclever/?hl=en">Instagram|</a> 
<a href="http://www.youtube.com/@ErrorMakesClever">YouTube</a>
</center>
</body>
</html>
```
- This section repeats the links to registration, Instagram, and YouTube pages, similar to the previous link section.
- **`</body>`**: Closes the body tag, indicating the end of visible content.
- **`</html>`**: Closes the HTML document.

## Summary of the Code
The HTML code provides a webpage with:
1. **Academy Introduction:** Introduction to "Error Makes Clever Academy."
2. **Registration Form:** A form that accepts user details like name, age, gender, and course selection.
3. **YouTube Video Embedding:** An embedded YouTube video.
4. **Full-Stack Development Overview:** Information about full-stack development, technologies used, and a table layout.
5. **External Links:** Links to the homepage, Instagram, and YouTube channel for more interaction.
