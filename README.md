# Shape Detection Project

This Python project detects geometric shapes in images using OpenCV.  
It identifies triangles, squares, rectangles, pentagons, and circles, and visualizes the results with annotated images.

## Features
- Detects multiple geometric shapes in an image
- Uses contour detection and shape approximation
- Visualizes results with labeled contours
- Input and output images stored in `assets` folder

## Folder Structure
shape-detection/
│
├─ assets/ # Input and output images
│ ├─ annotated_output.png
│ └─ shapes_input.png
│
├─ shape_detection.ipynb # Main Jupyter Notebook containing the shape detection code
├─ requirements.txt # Python dependencies
└─ README.md


## Installation

1. Clone the repository:

```bash
git clone https://github.com/chaudharywaqeeahmad/shape-detection.git
cd shape-detection

2. Create a virtual environment (optional but recommended):

python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows

3. Install the dependencies:

pip install -r requirements.txt


## Installation

1. Open the Jupyter Notebook:

jupyter notebook shape_detection.ipynb

2. In the notebook, set the path to your input image if
needed (update the args["image"] variable).

3. Run the notebook cells sequentially to execute the shape detection and visualize results.

4. The output image will show detected shapes with labels.
Example:
Input image: assets/shapes_input.png
Output image: assets/annotated_output.png          with annotated shapes

