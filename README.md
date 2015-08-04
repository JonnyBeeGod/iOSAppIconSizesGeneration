# iOSAppIconSizesGeneration
This automator script takes a single image file and generates various copies of it scaled to the appropriate App Icon sizes for the Xcode Assets catalog. For best results the input image file should have a resolution greater than 180 * 180 px. In addition, loss-less compressed file formats (png / tiff / bmp) should produce images of better quality.

### Supported input image file types
* .bmp
* .gif
*. jpg or .jpeg
* .jp2
* .png
* .tif or .tiff

### Output image file type
* .png

###  Generated image resolutions
* 180 * 180
* 152 * 152
* 120 * 120
* 87 * 87
* 80 * 80
* 76 * 76
* 58 * 58
* 40 * 40
* 29 * 29

