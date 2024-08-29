# Image Processor

This is a simple Python-based image processing tool that allows you to perform various operations on images, such as resizing, rotating, adjusting brightness, and applying filters. The project uses the `PIL` (Python Imaging Library) module for image manipulation.

## Features

- **Resize Image**: Change the dimensions of an image to specified width and height.
- **Rotate Image**: Rotate the image by a specified number of degrees.
- **Adjust Brightness**: Modify the brightness of an image. Use a factor greater than 1 to increase brightness and less than 1 to decrease it.
- **Apply Filters**: Apply different filters to the image, such as blur, contour, or emboss.

## Installation

To use this project, you need to have Python installed along with the `Pillow` library, which is a fork of the original `PIL` library.

1. Clone the repository or download the code.

    ```bash
    git clone https://github.com/your-username/image-processor.git
    cd image-processor
    ```

2. Install the required dependencies using `pip`.

    ```bash
    pip install Pillow
    ```

## Usage (continued)

2. Follow the on-screen prompts to choose an image processing operation:
   - Enter the path to your image file.
   - Choose an operation from the menu:
     1. **Resize Image**: Input the new width and height for the image.
     2. **Rotate Image**: Input the degrees by which you want to rotate the image.
     3. **Adjust Brightness**: Input a brightness factor (e.g., `1.5` to increase brightness, `0.8` to decrease it).
     4. **Apply Filter**: Choose a filter from `blur`, `contour`, or `emboss`.

3. The processed image will be saved with a descriptive filename indicating the operation performed (e.g., `image_resized.jpg`, `image_rotated.jpg`).

## Example

Here’s an example of how to use the tool:

1. **Resize an Image:**
    - You choose option `1` from the menu to resize an image.
    - Provide the path to your image (e.g., `example.jpg`).
    - Enter the new dimensions (e.g., width: `800`, height: `600`).
    - The resized image will be saved as `example_resized.jpg`.

2. **Rotate an Image:**
    - You choose option `2` to rotate an image.
    - Provide the path to your image.
    - Enter the degrees to rotate (e.g., `90` degrees).
    - The rotated image will be saved as `example_rotated.jpg`.

## Project Structure

- `image_processor.py`: The main script containing the `ImageProcessor` class and the command-line interface for interacting with the user.

## Requirements

- Python 3.x
- Pillow library
pip install -r requirements.txt
