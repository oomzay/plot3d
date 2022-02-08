## Overview

A 3D surface plotting application that should work in any javascript-enabled web browser.

The application reads x,y,z coordinates from a file and displays a colorful surface plot that can be rotated and zoomed.

## Screenshot

![Screenshot1](screenshots/Screenshot1.png)

## Getting Started

Open [plot3d.html](plot3d.html) in a browser and load a local file with 3D data points in CSV format.

## Example data file

      # Example data file.
      #
      # The file name is used as the title of the plot.
      #
      # Comments and blank lines in the file are ignored.
      #
      # If the first CSV row contains 3 text strings these
      # are used to label the three axis.
      #
      x-axis-label,y-axis-label,z-axis-label
      0,0,0
      1,1,1

## License

Distributed under the MIT License. See [LICENSE.txt](LICENSE.txt) for more information.
