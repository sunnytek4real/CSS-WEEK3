/* style.css */

/* 1. Selector for a class */
.header {
  background-color: #333;
  color: Blue;
  padding: 20px;
  font-family: 'Arial', sans-serif;
}

/* 2. Selector for an ID */
#main-content {
  margin: 20px auto;
  border: 2px solid #000;
  padding: 20px;
  background-color: #f4f4f4;
  font-family: 'Georgia', serif;
}

/* 3. Selector for an element with a class and applying color and typography */
p.content {
  color: #333;
  font-size: 16px;
  line-height: 1.5;
}

/* Styling an image */
img {
  border: 5px solid #ddd;
  padding: 5px;
  box-shadow: 2px 2px 5px #aaa;
  transition: all 0.3s ease;
  cursor: pointer;
}

/* Hover effect on the image */
img:hover {
  border-color: #000;
  box-shadow: 5px 5px 10px #000;
}
<!DOCTYPE html>
<html>
<head>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="header">
    <h1>Welcome to Our Website</h1>
  </div>

  <div id="main-content">
    <p class="content">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean in ipsum id mi luctus congue at in sem. Nullam eget sapien non ligula tristique aliquet. Vivamus non nisi eleifend, ultricies mi nec, porta mauris. Integer euismod congue mi, sed rhoncus est. Phasellus nec luctus nibh.</p>

    <img src="example.jpg" alt="Example Image" class="img-class">
  </div>

  <p class="content">This is another paragraph with the same class styling.</p>
</body>
</html>
