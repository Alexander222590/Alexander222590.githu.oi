<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My First Website</title>
  <style>
    /* CSS for formatting and design */
    body {
      font-family: Arial, sans-serif;
      margin: 20px;
      background-color: #f5f5f5;
    }

    h1 {
      color: #2c3e50;
    }

    p {
      color: #34495e;
      font-size: 18px;
    }

    a {
      color: #3498db;
      text-decoration: none;
    }
  </style>
</head>
<body>
  <!-- HTML elements go here -->
  <h1>Welcome to My Website</h1>
  <p>This is a paragraph with some <b>bold</b> and <i>italic</i> text.</p>
  <p>Visit <a href="https://example.com">this website</a> for more information.</p>

  <h2>Unordered List</h2>
  <ul>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
  </ul>

  <h2>Ordered List</h2>
  <ol>
    <li>First Item</li>
    <li>Second Item</li>
    <li>Third Item</li>
  </ol>

  <h2>Image Example</h2>
  <img src="https://via.placeholder.com/150" alt="Placeholder Image">

  <h2>Button with JavaScript</h2>
  <button onclick="alertMessage()">Click Me!</button>

  <script>
    // JavaScript function for interactivity
    function alertMessage() {
      alert('Hello! Welcome to my website.');
    }
  </script>
</body>
</html>
