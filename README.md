# Gigazit-DS

* Content: *

This Python script demonstrates how to convert pixel locations within an image to their corresponding x and y coordinates.

* Assumptions **:

-->The image format is compatible with Pillow (e.g., JPEG, PNG).

* Running the script *:

--> Saved the script as pixel_to_coordinates.py and the 

--> Saved the image file as "cat1.jpeg" in the script with the actual path to the image file.

* Run the script using the command:*

--> python pixel_to_coordinates.py

* Explanation *:

The script opens the image using Pillow and retrieves its dimensions (width and height). It then checks if the provided pixel location is within the image boundaries. If valid, it returns the x and y coordinates as a tuple.

Imagine a grid system overlaid on your image. Each square on the grid represents a single pixel. The numbering starts from (0, 0) at the top-left corner. The x-coordinate increases as you move to the right, and the y-coordinate increases as you move down.

In this case, the pixel with coordinates(250, 180) is located:

250 pixels to the right of the leftmost edge (x-axis).
180 pixels down from the topmost edge (y-axis).
Therefore, the provided output simply confirms that the coordinates you specified (250, 180) correctly represent the actual location of a pixel within your image.
