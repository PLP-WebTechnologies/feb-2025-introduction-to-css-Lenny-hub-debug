# Introduction to CSS

## Objectives
Link an external CSS file to an HTML document.
Apply basic styling using selectors.
Use colors, fonts, and spacing effectively.

## Instructions

Create a style.css file.
Apply CSS to a HTML page.
Style elements using:
Classes and IDs.
Color and typography.
Margins, paddings, and borders.

>[!NOTE]
>  - Include at least:
>  - Use of 3 selectors
>  - Style an image
>  - Margin, Padding & Borders
>  - Different font

# Tasks
 - Link an external CSS file.
 - Apply at least 3 different selectors.
 - Improve readability and aesthetics.

Happy Coding! 💻✨
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Styled Page</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <h1 id="main-title">Welcome to My Page</h1>

  <div class="content">
    <p>This is a paragraph styled using an element selector. The font, spacing, and layout are adjusted for readability and aesthetic.</p>
    <p class="highlight">This content block is using a class selector and has padding, margin, and border for structure.</p>
    <img src="img.jpg/400" alt="Sample Image" class="responsive-img">
  </div>

</body>
</html>


/* ID selector */
#main-title {
  color: #2c3e50;
  font-family: 'Georgia', serif;
  font-size: 2.5em;
  margin-bottom: 20px;
  text-align: center;
}

/* Class selector */
.content {
  font-family: 'Arial', sans-serif;
  color: #333;
  padding: 20px;
  margin: 10px auto;
  max-width: 800px;
  border: 1px solid #ccc;
  background-color: #f9f9f9;
}

/* Element selector */
p {
  line-height: 1.6;
  margin-bottom: 15px;
}

/* Style an image */
img.responsive-img {
  width: 100%;
  max-width: 400px;
  height: auto;
  border: 3px solid #3498db;
  border-radius: 10px;
  display: block;
  margin: 20px auto;
}
