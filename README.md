# Colour-Detection
Allows users to detect the color name of any pixel in an image by double-clicking on it. The script reads an image file and displays it in a window. When the user double-clicks on any point in the image, the script identifies the color of that pixel based on a predefined list of colors stored in a CSV file. The detected color name and its RGB values are then displayed on the image.

## Features
- Color Detection: Identifies the color name of any pixel in the image.
- Dynamic Text Display: Automatically adjusts text color for better visibility depending on the background color.
- Mouse Interaction: Uses mouse double-click events to select pixels for color detection
- CSV File Handling: The application reads data from a csv file and outputs relevant data from the csv file

## Instructions
Install the required packages if not already installed:
  - Python 3.x
  - OpenCV
  - Pandas
    
Download all the files in the repo  and use the command line to run the script with the required image path as an argument:
```````
python color_detection.py -i <path_to_image>
```````
## Future Enhancements
- Improved Color Matching: Implement more advanced algorithms for color detection.
- GUI Improvements: Add more interactive features or enhance the visual presentation.
- Save Results: Add functionality to save the detected colors and their positions in an output file.

