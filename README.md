# Software Team

Areas of focus:

- Computer Vision
- Controllers
- Data analytics
- Front End UI/UX

## Goals
1. Familiarity with OpenCV image processing
2. Experience creating custom Arduino libraries in C++
3. Knowledge of K-NN, linear classifiers, and other basic ML concepts
4. Ability to code quickly in Python


## Python Tasks
- Download Python (3.1 preferred)
- Read in an argument from the command line and print it. Use `import sys` and indexing into `sys.argv` to grab command line arguments (ex. `./python printtest.py falcon9` will print `falcon9`)
- Open [this file](http://www.gutenberg.org/files/1184/1184-0.txt) and display contents to the terminal line by line
- Check if a file exists - if not, create it
- Open a file and write `testing...1...2...3` to it
- Write a function `def countdown( start )` which takes an `int` value and decrements that `int` once per second. Meanwhile, print the current value to terminal. At zero, print `We have liftoff`.
- Write a class 'class rocket' whose initializer `def __init__( start )` takes an `int` value. For an instance of `rocket` named `rkt`, `rkt.launch()` should begin the `countdown` method, using the `int` passed into the `rocket` initializer.
- Tie it together. Write a program called `rocketlaunch.py` which takes an `int` as a command line argument, creates an instance of `class rocket`, passes that `int` to the rocket, then begins a countdown. Format your print statements to occur on one line like so:

> $ ./python rocketlaunch.py 3
>
> 3...2...1...We have liftoff

For [this data](http://m-selig.ae.illinois.edu/ads/coord/b29root.dat):
- Return an array of the form [[float, float]] by parsing the float pairs in the file, removing all whitespaces and header info
- Plot on an XY plane (hint: import matlibplot.pyplot as plt).

Notes:
- Use `str.split(' ')` to split a string into an array, using whitespaces as a delimeter (no whitespaces in array).
- After obtaining the float values from the string, ensure they are actually in `float` format with `float(str)`.
- To convert a list of strings into a list of floats, try `xs = [ float(x) for x in list_of_strings ]`
- You can choose to download the files and place them in the same directory as your python file, or you can use the urllib2 library to obtain the files from the url during runtime



## OpenCV Image Processing

- Download [OpenCV]('http://opencv.org/downloads.html')

All tasks performed in Python. `import cv` or `import cv2`

For [this image](chip.png):
- Open image and display (`imshow()`).
- Split the image into its red, green, and blue channels, and display all three images in the same window.
- Convert original image to grayscale, and write image as new file labeled `chip2.jpg`.
- Resize the image to 250x250, and write image to new file labeled `chip_resized.jpg`.
- Create a histogram of the grayscale image. The histogram is a bar graph where the x axis are the values 0 (black) through 255 (white), and the y axis is the number of pixels in the image with that value.
- Binarize the image. You can use 

For [this image](coin.jpg):
- Write a python script that returns how many 'regions' are in this image. Hint: convert to grayscale, binarize. Start with the topmost, leftmost pixel, and explore.

Notes: If you are unfamiliar with search algorithms such as DFS/BFS, please consult the software lead.

-
