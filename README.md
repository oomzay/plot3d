## Overview

[A single-page web app for visualising and exploring 2.5D datasets](plot3d.html).

The app reads a set of x,y,z data points from a CSV file and displays a colorful 3D model of the z-surface derived by [Delaunay triangulation](https://en.wikipedia.org/wiki/Delaunay_triangulation). The model can be interactively navigated.

## Screenshot

![Screenshot1](screenshots/Screenshot1.png)

## Getting Started

Just open [plot3d.html](plot3d.html) in your browser and load a 2.5D dataset from file.

Use a mouse or touch to navigate the 3D model.

Dataset files can be dragged and dropped into the application if the host supports this.

## Dataset File Format

Data point x,y,z coordinates must be stored in (UTF-8) CSV format. If the first CSV row contains any text then the values from that row are used to label the x,y & z axis. Lines starting with '#' and blank lines are ignored. The file name is used as the title of the model.

### Example Data File

      x-label,y-label,z-label      
      0,0,0
      1.0,2.1,3.2
      2.3,3.1,4.2

## License

Distributed under the MIT License. See [LICENSE.txt](LICENSE.txt) for more information.
