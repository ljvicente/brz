# brz
Stupid, recursive bulk trimmer and resize tool for images with #FFF background

**Installation**

Make sure `mogrify` and `jpegoptim` is installed on your system.  

Download the script and make it executable:

`wget https://raw.githubusercontent.com/ljvicente/brz/master/brz && chmod a+x brz`

**Example Usage** 

Run the executable and pass the image folder path as the first parameter. And, second parameter as the *inner (non-white space) image size*, *outer (white space canvas size)*:

`./brz /path/to/folder/ 1000x1000,1200x1200`

You can also use the predefined shape and size:

`./brz /path/to/folder/ square`

or:

`./brz /path/to/folder/ rectangle`

