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
- Download Python
- Read in an argument from the command line and print it. Use `import sys` and indexing into `sys.argv` to grab command line arguments (ex. `./python printtest.py falcon9` will print `falcon9`)
- Open [this file](http://www.gutenberg.org/files/1184/1184-0.txt) and display contents to the terminal line by line
- Check if a file exists - if not, create it
- Open a file and write to it
- Write a function `def countdown( start )` which takes an `int` value and decrements that `int` once per second. Meanwhile, print the current value to terminal. At zero, print `We have liftoff`.
- Write a class 'class rocket' whose initializer `def __init__( start )` takes an `int` value. For an instance of `rocket` named `rkt`, `rkt.launch()` should begin the `countdown` method, using the `int` passed into the `rocket` initializer.
- Tie it together. Write a program called `rocketlaunch.py` which takes an `int` as a command line argument, creates an instance of `class rocket`, passes that `int` to the rocket, then begins a countdown. Format your print statements to occur on one line like so:

> $ ./python rocketlaunch.py 3
> 
> 3...2...1...We have liftoff

For [this data](http://m-selig.ae.illinois.edu/ads/coord/b29root.dat):
- Return an array of the form [[float, float]] by parsing the float pairs in the file, removing all whitespaces and header info 
- Plot on an XY plane (hint: import matlibplot.pyplot as plt). 

Notes: You can choose to download the files and place them in the same directory as your python file, or you can use the urllib2 library to obtain the files from the url during runtime

## OpenCV Tasks

TBA
