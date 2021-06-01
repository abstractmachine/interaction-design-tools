# Media Design Tools
This is a list of all the basic tools that any student of Media Design should have access to. While there is an infinite variety of possible tools that can be used in any project, this is the list of the core basics that should be downloaded/configured on your personal computer.

## Terminal
Figure out where the Terminal is on your computer.

- macOS: `cmd` + `space` and type `Terminal`
- Windows: 
- Linux: 

Common commands from within the terminal are: `cd` change directory, `ls` list files in current directory, `mkdir` make directory, `cp` copy file, `mv` move or rename a file/directory.

The terminal is powerful. Be careful: you can break things.

## VS Code
Microsoft Visual Studio Code is an open-source code editor. You can use to access/code/talk to all sorts of software, languages, and machines. You can use it to make websites, program an Arduino microcontroller, control a Raspberry PI, code a game in Unity, write Twine poetry, draw P5 sketches, and gazillion other things.

<https://code.visualstudio.com/download>

Once you have downloaded and installed VS Code on your machine, you should install the following "exensions" to VS Code: `Menu` > `View` > `Extensions`

- [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
- [p5.vscode](https://marketplace.visualstudio.com/items?itemName=samplavigne.p5-vscode)
- [Live Share](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare)
- [SSH Tools](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-ssh)
- [GIT Lens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
- [Python for Visual Studio](https://marketplace.visualstudio.com/items?itemName=ms-python.python)

To make Unity (see below) work with VS Code, you should install the following :
- [Dot Net Core SDK](https://dotnet.microsoft.com/download)
- **For macOS users**, downlad the latest [Mono](https://www.mono-project.com/download/stable/) installer
- [C# Extension](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csharp)
- [Unity Debugger Extension](https://marketplace.visualstudio.com/items?itemName=Unity.unity-debug) (optional)
- [Unity Snippets Extension](https://marketplace.visualstudio.com/items?itemName=kleber-swf.unity-code-snippets) (optional)

If after all that you are still having problems reading your Unity scripts in VS Code, or cannot use the handy autocomplete features, read the following Microsoft document: [Unity Development with VS Code](https://code.visualstudio.com/docs/other/unity).

## P5
P5 is the JavaScript evolution of the [Processing](http://processing.org) project and is essential for learning the basics of *creative coding*.

<https://p5js.org>

You can write P5 "sketches" using the `P5.vscode` extension for VS Code (cf. above). Or you can code your sketches directly inside the online P5 editor, which is handy for quickly prototyping any idea from whatever machine you are on: just open a browser, sign in, and starting coding an interactive sketch:

<https://editor.p5js.org>

Make sure you create an account in order to save your work and access your previous sketches.

If you are already experienced in creating web pages, you can download the latest "complete library" version of P5 to your computer. This will also allow you to creatively code offline. In this way, you would code your P5 sketches using VS Code (cf. above):

<https://p5js.org/download/>

## Arduino
Arduino allows you to program interactions with the physical world. You should always have an Arduino UNO or an Arduino Leonardo at your disposal, along with a basic set of core electronics such as a breadboard, wires for prototyping, buttons, LEDs and a servomotor or two.

- [Arduino Leonardo](https://store.arduino.cc/arduino-leonardo-with-headers)
- [Arduino Uno](https://store.arduino.cc/arduino-uno-rev3)

There are many starter kits containing everything you need to get started (circuit + electronic components):

- [Elegoo Starter Kit](https://www.amazon.fr/Elegoo-Démarrage-dUtilisation-Débutants-Professionnels/dp/B01JD2Z5XW?ref_=ast_sto_dp)

If you already feel comfortable with the Arduino platform, and wish to have access to more advanced features such as wifi or bluetooth, you can opt instead for an ESP32-based microcontroller:

- ESP32 link

Download the Arduino software here:

<https://www.arduino.cc/en/software>

Arduino is simple software, so great for beginners. But you can also use VS Code (cf. above) to code your Arduino projects.

## Unity
Always start by installing the Unity Hub. **Ignore the "Choose your version of Unity" button**. You should instead install your preferred version of Unity directy from with the "Unity Hub":

<https://unity3d.com/fr/get-unity/download>

Create a free account on the Unity website:

<https://id.unity.com/account/new>

Open Unity Hub on your computer and login to your account. From this hub, download the latest `LTS` version of Unity. `LTS` is the "Long Term Support" version of Unity and will last for at least two-years, i.e. the length of a masters programme. Current we are using Unity 2020.3.x (the last number is just bug fixes and is compatible with any other 2020.3.x release).

## Cinema 4D
We use Cinema 4D for creating speculative scenarios, world building, and exploring narrative through 3D. It is not the ideal tool for CAD-style design of physical objects.

There is a very affordable a "teacher & student" licence for Cinema 4D:

<https://www.maxon.net/en/buy/students-teachers>

If you are already an expert in some other "animation" or "game design" oriented 3D tool such as Blender (cf. below), Maya, 3DS Max, etc., you can stick with that tool. There are many ways to make 3D.

## Blender
Blender is a free, open-source alternative to Cinema 4D, and is currently the rising platform for all things animation/game 3D. It is not the ideal tool for CAD-style design of physical objects. If you know Maya inside and out, good for you. If you don't and want to learn all the basic tools of asset creation for games, along with rigging tools, start with Blender:

<https://www.blender.org/download/> 

## GIT
We use Git to backup, collaborate, and create historical breadcrumbs of our work.

*Why is this important?* You will **always** make mistakes, and by constantly creating backups of your work via Git, you can easily return to a previous version before your latest bender, high as a kite where you had an awesomesauce revolutionary idea that totally broke everything you had built up to that point; calm down; deep breath; pour yourself a tea; move back to a previous `git commit` from when you were more sober; get back to work making your awesome thing.

Make sure Git is installed on your machine. Open a Terminal (cf. above) and type `git` from the command line. You should see a list of possible Git functions.

To save your Git backups online, open free accounts on the two following websites:

- <https://bitbucket.org>
- <https://github.com>

You will share code from your various projects and download code from various contributors via these two websites, as well as other popular Git hosting sites.

## Package Manager
- macOS
	- Install `brew`
- Linux
	- `apt-get`
- Windows
	- ???

## Python
Install a Python Virtual Environment.

```
```

Install the latest Python version to your virtual environment.

```
```

Install the Python package manager `pip3`

```
```

Make sure you have the following base Python packages installed:

- [Pytoch](https://pytorch.org/get-started/locally/)
- [Numpy](https://numpy.org/install/)
- [Tensorflow](https://www.tensorflow.org/install/pip?hl=fr)

## Runway ML
Runway is great tool for exploring machine learning via graphical user interface :

<https://runwayml.com>

## Miro
We use Miro to collaboratively flesh out ideas, make mindmaps, write story trees, design website navigation, and all sorts of other things.

<https://miro.com/>

## Figma + Bravo
Figma is one of many possible tools you can you to make interactive wireframes of an app or website.

<https://www.figma.com>

By adding Bravo into the mix, you can convert your Figma prototype into an actul working app that you can install onto your phone.

<https://www.bravostudio.app>