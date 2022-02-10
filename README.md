## Overview

[A web app for visualising 2.5D datasets](plot3d.html).

The app reads x,y,z coordinates from a CSV file and presents a colorful 3D model of the z-surface that can be rotated, zoomed and panned.

## Screenshot

![Screenshot1](screenshots/Screenshot1.png)

## Getting Started

Just open [plot3d.html](plot3d.html) in a browser and load a dataset. Use a mouse or touch to navigate the 3D model.

Dataset files can be dragged and dropped into the application if the host supports this. 

## Dataset File Format

The x,y,z coordinates must be in (UTF-8) CSV format. Many applications can output data in this format.

If the first CSV row contains text, rather than numbers, then the values from that row are used to label the x,y & z axes. 

### Example Dataset File

      x-label,y-label,z-label      
      0,0,0
      1.0,2.1,3.2
      2.3,3.1,4.2

Any lines starting with '#' and blank lines are ignored.

The dataset file name is used as the title of the model.

## Issues and Requests

Please report any issues and make any requests on the development site: [https://github.com/oomzay/plot3d/issues](https://github.com/oomzay/plot3d/issues)

## Developers

If you want to contribute please visit the development site: [https://github.com/oomzay/plot3d](https://github.com/oomzay/plot3d)

## License

Distributed under the MIT License. See [LICENSE.txt](LICENSE.txt) for more information.
