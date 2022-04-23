# LZW_algorithm
LZW algorythm realized in  black and white images with help of PIL

Firstly, I use PIL library to convert my image to black and white one. Also it helps to create an array of pixels according to the shade of it(0-255).

After it I used LZW algorithm to compress my image. I converted my array to a string and worked with it.

![1_tYjAU32Z9SIt1tz_1CRxFg](https://user-images.githubusercontent.com/92577132/164896073-9b6319c0-9cad-4dc5-bb81-a0c052dc0bc8.png)

For decompression I use the result of function which compress my image(returns the list of integers) and convert in again to the text.

Final string can be converted to aray again and return our image.

Generally, algorithm works, but I dislike the way how it makes.
