# Image-to-Sketch-Converter
#### *Fork this repository to tweak the code!
## This converter uses OpenCV
It converts the image to grayscale just to ensure the colored images are managed properly. Then it is inverted by the bitwise not operation and blurred. The blurred image is again inverted. Later, the grayscale image and the inverted and blurred images are divided to gain an image which looks like a sketch.
