<h1 align="center">
  Snake Game - Python
</h1>
<p align="center">
  A simple snake game created using Python
</p>

![demo](https://raw.githubusercontent.com/Abhijith14/SnakeGame-PyGame/master/image.gif)

<br>
<br>


## 📕 Installation

### 🕷️ Create an environment
Whatever you prefer (e.g. `conda` or `venv`)
```console
mkdir myproject
$ cd myproject
$ python3 -m venv venv
```

### 🕷️ Activate it
Windows:
```console
venv\Scripts\activate
```
Mac / Linux:
```console
. venv/bin/activate
```
### 🕷️ Install Dependencies

You only need `PyGame`:
 ```console
pip install pygame
 ```


## 👨‍💻 Usage
Run
```console
python game.py
```
This will start the game.<br>
Use:
```console
Up Arrow for going UP
Right Arrow for going RIGHT
Down Arrow for going DOWN
Left Arrow for going Left
```

## ⚙️ Customize
Have a look at [game.py](game.py). You can change the game variables according to your own use case. <br>
Change the colours of the game elements over here.
```
# rgb colors
WHITE = (255, 255, 255)
RED = (200,0,0)
BLUE1 = (0, 0, 255)
BLUE2 = (0, 100, 255)
BLACK = (0,0,0)
```
Default BLOCK_SIZE (Size of a block in the game) and SPEED (speed of snake) is set to 20.
```
BLOCK_SIZE = 20
SPEED = 20
```
In the init function of class SnakeGame; the parameters w and h are the width and height of your game window.
```
def __init__(self, w=640, h=480):
        self.w = w
        self.h = h
```
<br>


### 🛠️ Built With

* [Python 3.7](https://www.python.org/) - Creating Project


### ❤️ Authors

* **Abhijith Udayakumar** - *Design & Development* - [Abhijith14](https://github.com/Abhijith14)

<br>
<br>

## 🚨 Forking this repo (please read!)

_**yes, with attribution**_.

I value keeping my work open source, but as you all know, _**plagiarism is bad**_. It's always disheartening whenever I find that someone has copied my work without giving me credit. I spent a non-trivial amount of effort building and designing this project, and I am proud of it! All I ask of you all is to not claim this effort as your own.


### TL;DR

Yes, you can fork this repo. Please give me proper credit by linking back to [Abhijith14/SnakeGame-PyGame](https://github.com/Abhijith14/SnakeGame-PyGame). Thanks!
