# Random Colors!

Laurel Barrett

## Assignment Description 

This project involves writing a program that results in the built-in Arduino RGB LED lighting up with random colors when the button (input) is pressed. The code must ensure that the random lights only flash when the button is pressed on, not when it is off. This is achieved by utilizing the implementation of Random Seed and RandPin for the first time in this course.

### Photo of Arduino Kit Output with Working RGB LED

![Working RGB](https://laurel525.github.io/assets/img/IMG_7501.jpeg)

#### Tip For My Past Self...

I would remind myself to specifically turn off each pin using analogWrite. I spent a long time confused as to why my LED wouldn't turn off when I unpressed the button, only to realize the solution was as simple as turning off each individual pin instead of using randPin again. 
