## Paint Clone

### Description:
This repository contains a web-based paint application resembling MS Paint. It allows users to draw on a canvas using various tools such as brushes, erasers, and buckets. Users can also save, load, and clear their drawings.

### Features:
- **Brush Tool:** Allows users to draw lines of customizable size and color.
- **Bucket Tool:** Fills areas of the canvas with a selected color.
- **Eraser Tool:** Removes drawn elements from the canvas.
- **Clear Canvas:** Clears the entire canvas to start afresh.
- **Save/Load/Clear Local Storage:** Enables users to save their drawings locally, load saved drawings, or clear saved data.
- **Download Drawn Image:** Allows users to download their drawings as image files.
- **Responsive Design:** The application is designed to adapt to different screen sizes.

### Getting Started:
To start using the Paint Clone application locally, follow these steps:

1. **Clone the Repository:** Use the following command to clone the repository to your local machine:
   ```
   git clone https://github.com/osama206/paint-clone.git
   ```

2. **Navigate to the Directory:** Enter the project directory using:
   ```
   cd paint-clone
   ```

### Usage:
- **Open the Application:** Open the `index.html` file in a web browser to launch the paint application.
- **Select Tools:** Choose different tools from the top toolbar to draw, erase, fill, or clear the canvas.
- **Adjust Settings:** Modify brush size and color using the controls provided.
- **Save/Load Drawings:** Use the provided buttons to save, load, or clear drawings from local storage.
- **Download Image:** Download the drawn image using the download button.

### Demo:
You can view a live demo of the Paint Clone application [here](https://osama206.github.io/paint-clone).

### Files Included:
- `index.html`: HTML file containing the structure of the paint application.
- `style.css`: CSS file containing styles for the application layout.
- `script.js`: JavaScript file containing functionality for the paint application.
- `jscolor.js`: JavaScript library for color picker functionality.

### Credits:
- **[Font Awesome Icons](https://fontawesome.com/icons?d=gallery&m=free):** Utilized for toolbar icons, enhancing the visual representation of various tools and functionalities.
- **[JSColor Color Input Library](https://jscolor.com/):** Integrated to provide users with a color picker tool, allowing them to choose custom colors for drawing.
- **[W3Schools Custom Input Range Slider](https://www.w3schools.com/howto/howto_js_rangeslider.asp):** Referred to for implementing a custom slider input, which enables users to adjust brush size dynamically.
- **[Mozilla Canvas API](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial):** Consulted for guidance on canvas drawing operations, enabling the implementation of drawing functionalities like line drawing, erasing, and filling.
- **[W3Schools window.innerHeight/Width](https://www.w3schools.com/jsref/prop_win_innerheight.asp):** Referenced for retrieving window dimensions, ensuring a responsive design that adapts to different screen sizes.
- **[Mozilla Canvas 2D Context](https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D):** Used for accessing the 2D drawing context of the canvas element, enabling drawing operations on the canvas.
- **[Mozilla Canvas getBoundingClientRect](https://developer.mozilla.org/en-US/docs/Web/API/Element/getBoundingClientRect):** Employed to retrieve the bounding rectangle of the canvas element, facilitating accurate positioning of mouse events for drawing.
- **[Mozilla Drawing Shapes on Canvas](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_shapes):** Consulted for techniques on drawing shapes on the canvas, enhancing the drawing capabilities of the application.
- **[W3Schools Mouse Events](https://www.w3schools.com/jsref/obj_mouseevent.asp):** Referred to for handling mouse events such as mouse down, mouse move, and mouse up, enabling interactive drawing functionalities.
- **[Mozilla Canvas toDataURL](https://developer.mozilla.org/en-US/docs/Web/API/HTMLCanvasElement/toDataURL):** Utilized to convert the content of the canvas to a data URL, enabling users to download their drawings as image files.
