
/* styles.css */

/* Element Selector:  Styles all paragraph elements */
p {
  font-family: 'Arial', sans-serif;  /* Sets the font family */
  color: #333;             /* Sets the text color to a dark gray */
  line-height: 1.6;         /* Improves readability by adding space between lines */
}

/* Class Selector: Styles elements with the class "highlight" */
.highlight {
  background-color: #fef08a;  /* Sets a yellow background color */
  color: #1e293b;          /* Sets the text color to a very dark blue */
  padding: 5px 10px;       /* Adds 5px of padding on top and bottom, 10px on left and right */
  border-radius: 5px;      /* Rounds the corners of the background */
  font-weight: 600;        /* Makes the text bold */
}

/* ID Selector: Styles the element with the ID "main-heading" */
#main-heading {
  font-family: 'Verdana', sans-serif; /* Sets a different font family */
  color: #4f46e5;          /* Sets the text color to a shade of purple */
  font-size: 2.5em;         /* Sets the font size (em is a relative unit) */
  margin-bottom: 20px;      /* Adds 20px of margin below the heading */
  text-align: center;      /* Centers the heading */
}

/* Styling an image */
img {
  border: 4px solid #a855f7;  /* Adds a 4px solid purple border */
  border-radius: 8px;      /* Rounds the corners of the image border */
  margin: 20px auto;       /* Adds 20px margin above and below, centers the image horizontally */
  display: block;          /* Makes the image a block element, allowing for margin auto */
  max-width: 80%;          /* Ensures the image doesn't get too wide */
  height: auto;           /* Maintains the image's aspect ratio */
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); /* Adds a subtle shadow */
}

/* Example of margins, padding, and borders */
.box {
  margin: 30px;           /* Adds 30px margin on all sides of the box */
  padding: 20px;           /* Adds 20px padding inside the box */
  border: 2px dashed #6b7280;  /* Adds a 2px dashed gray border */
  background-color: #f3f4f6;  /* Sets a light gray background color */
  border-radius: 10px;     /* Rounds the corners of the box */
  text-align: center;
  width: 200px;          /* sets the width of the box*/
}

/* Different font for a specific element */
.special-text {
  font-family: 'Georgia', serif;  /* Uses the Georgia font, a serif font */
  font-style: italic;       /* Makes the text italic */
  color: #10b981;          /* Sets the text color to a green */
}
