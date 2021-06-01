# Interaction Design Tools
This is a list of some of the basic tools that any student of interaction design should have access to. 

There is an infinite variety of possible tools that can be used in any project, so this list is by definition incomplete. These are just some of the core basics that should be downloaded/configured on your personal computer.

This list is oriented more towards the *creative coding*, and/or the *make-semi-functional-prototypes* approach, than the mockup *UX* or *UI* style of teaching interaction design.

Not everything here is open-source, although there are open-source alternative listed, when available.

- - -

## Storytelling

### Twine/Twee
Twine is a tool for making non-linear interactive text-based stories. It is also a great tool for getting started with interactivity. At some stage of each narrative project, we almost always prototype at least some part of our interactive stories in Twine. Twine is the best and fastest was to learn interactive branching narrative.

<https://twinery.org>

Twine comes with a branching, node-based visual tool.

Once we have used Twine to quickly find our voice, we either move to another tool, such as Fungus (cf. below), or design a more sophisticated story using Twine itself, or its pure text-based variant, named Twee:

<https://www.motoslave.net/tweego/>

The best way to write text-only Twee stories is from within VS Code (cf. below).

### Fungus
Fungus is a free, open-source plug-in for Unity (cf. below) that you can download via the Unity Asset Store.

[Fungus](https://assetstore.unity.com/packages/tools/game-toolkits/fungus-34184)

It is an entirely visual node-based programming tool, meaning you can design interactions using a system of interconnected visual "blocks" instead of writing text-based code.

Fungus is a fun way to start learning Unity and works well for youth-workshop introductions to 2D game creation in Unity. With very little basic knowledge of Unity you can get a lot done with Fungus.

- - -

## Code

### VS Code
Visual Studio Code is an open-source code editor, maintained by big old Microsoft. You can use it to access/code/talk to all sorts of software, languages, and machines. You can use it to make websites, program an Arduino microcontroller, control a Raspberry PI, code a game in Unity, write Twine poetry, draw P5 sketches, and gazillion other things. It is currently the de-facto tool for coding stuff in general.

<https://code.visualstudio.com/download>

Once you have downloaded and installed VS Code on your machine, you should install the following "exensions" to VS Code: `Menu` > `View` > `Extensions`

- [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
- [Live Share](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare)
- [p5.vscode](https://marketplace.visualstudio.com/items?itemName=samplavigne.p5-vscode) (cf. P5 below)
- [Python for Visual Studio](https://marketplace.visualstudio.com/items?itemName=ms-python.python)
- [Arduino extension](https://marketplace.visualstudio.com/items?itemName=vsciot-vscode.vscode-arduino) (cf. Arduino below)
- [GIT Lens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens) (cf. Git below)
- [SSH Tools](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-ssh)
- [Twee 3 Language Tools](https://marketplace.visualstudio.com/items?itemName=cyrusfirheir.twee3-language-tools) (cf. Twine/Twee above)

To make Unity (cf. below) work with VS Code, you should install the following :
- [Dot Net Core SDK](https://dotnet.microsoft.com/download)
- **For macOS users**, downlad the latest [Mono](https://www.mono-project.com/download/stable/) installer
- [C# Extension](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csharp)
- [Unity Debugger Extension](https://marketplace.visualstudio.com/items?itemName=Unity.unity-debug) (optional)
- [Unity Snippets Extension](https://marketplace.visualstudio.com/items?itemName=kleber-swf.unity-code-snippets) (optional)

If after all that you are still having problems reading your Unity scripts in VS Code, or cannot use the handy autocomplete features, read the following Microsoft document: [Unity Development with VS Code](https://code.visualstudio.com/docs/other/unity).

### P5
P5 is the JavaScript evolution of the [Processing](http://processing.org) project and is essential for learning the basics of *creative coding*.

<https://p5js.org>

You can write P5 "sketches" using the `P5.vscode` extension for VS Code (cf. above). Or you can code your sketches directly inside the online P5 editor, which is handy for quickly prototyping any idea from whatever machine you are on: just open a browser, sign in, and starting coding an interactive sketch:

<https://editor.p5js.org>

Make sure you create an account in order to save your work and access your previous sketches.

*Advanced users:* if you are already experienced in creating web pages, you can download the latest "complete library" version of P5 to your computer. This will also allow you to code offline. In this approach, you would write your P5 sketches using VS Code (cf. above):

<https://p5js.org/download/>

## Terminal
You should know where the Terminal is on your computer.

- macOS: `cmd` + `space` and type `Terminal`
- Windows: 
- Linux: 

Common commands from within the terminal are: `cd` change directory, `ls` list files in current directory, `mkdir` make directory, `cp` copy file, `mv` move or rename a file/directory.

The terminal is powerful. Be careful: you can break things.

## Package Manager
If you need to install commands in your terminal, you should use a "package manager".

- macOS
	- install `brew`
- Linux
	- use `apt-get` (installed by default on Raspberry Pi)
- Windows
	- ???

## GIT
We use Git to backup, collaborate, and create historical breadcrumbs of our work.

*Why is this important?* You will **always** make mistakes, and by constantly creating backups of your work via Git, you can easily return to a previous version before your latest bender, high as a kite where you had an awesomesauce revolutionary idea that totally broke everything you had built up to that point; calm down; deep breath; pour yourself a tea; move back to a previous `git commit` from when you were more sober; get back to work making your awesome thing.

Make sure Git is installed on your machine. Open a Terminal (cf. above) and type `git` from the command line. You should see a list of possible Git functions.

To save your Git backups online, open free accounts on the two following websites:

- <https://bitbucket.org>
- <https://github.com>

You will share code from your various projects and download code from various contributors via these two websites, as well as other popular Git hosting sites.

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

- [Pytorch](https://pytorch.org/get-started/locally/)
- [Numpy](https://numpy.org/install/)
- [Tensorflow](https://www.tensorflow.org/install/pip?hl=fr)

- - -

## 3D

## Unity
Unity is a "game engine", used for making 3D games or interactive experiences in general. Unity projects can be distributed on Mac, PC, Linux, Web, iOS, iPadOS, Android, Switch, Playstation, & XBox. It is the de-facto standard for AR, and is the dominant player in the world of VR. It's closest competitor is the Unreal Engine, or the more modest open-source project Godot.

Start by creating a free account on the Unity website:

<https://id.unity.com/account/new>

Always install whichever version of Unity you prefer via the "Unity Hub".

<https://unity3d.com/fr/get-unity/download>

**Ignore the "Choose your version of Unity" button** and instead install your preferred version of Unity directy from within this "Unity Hub". It will allow you to add and/or remove the various (large) components of your Unity installation at a later date, depending on the platform(s) you are targetting.

Open Unity Hub on your computer and login to your account. From this hub, download the latest `LTS` version of Unity. `LTS` is the "Long Term Support" version of Unity and will last for at least two-years, i.e. the length of a masters programme. Current we are using Unity 2020.3.x. The last number is just bug fixes and is compatible with any other 2020.3.x release.

*Special note:* constantly, always, without fail, someone will ask: "Isn't Unreal better than Unity?", "I read that Unreal is better than Unity", or "But I saw this YouTube video that says...", and so on. So: *tell me*, is it better? Yes, if you insist. But also: no, it isn't. Or, maybe. Or, whatever. Ask someone else. It's usually the wrong question. Unreal is not "better". It is "different", even if there is an overlap and they are definitely competitors. Unreal is awesome for cinematic immersive 3D world explorations. The latest Meta Human stuff is incredible, but Character Creator 3 works with Unity, so maybe it isn't that incredible after all. We'll see. Some people think it's easier to learn Unreal; many people think it's actually harder. Unity is ok to good for *some* of the things Unreal does really well, but is usually better because it does everything else, especially if you want to make 2D interactive games or experiences. But for 2D game design you can find a gazillion other alternatives. And there is always Godot, and even the cool 2D-oriented [P5.Play](https://molleindustria.github.io/p5.play/) plugin for P5 by none other than [Molleindustria](http://www.molleindustria.org). I don't know. Maybe you should ask better questions.

## Cinema 4D
We use Cinema 4D for creating speculative scenarios, world building, and exploring narrative through 3D. It is not the ideal tool for CAD-style design of physical objects.

There is a very affordable a "teacher & student" licence for Cinema 4D:

<https://www.maxon.net/en/buy/students-teachers>

If you are already an expert in some other "animation" or "game design" oriented 3D tool such as Blender (cf. below), Maya, 3DS Max, etc., you can stick with that tool. There are many ways to make 3D.

## Blender
Blender is a free, open-source alternative to Cinema 4D, and is currently the rising platform for all things animation/game 3D. It is not the ideal tool for CAD-style design of physical objects. If you know Maya inside and out, good for you. If you don't and want to learn all the basic tools of asset creation for games, along with rigging tools, just learn Blender:

<https://www.blender.org/download/>

- - -

## Physical Stuff

### Arduino
Arduino allows you to create interactions with the physical world.

<https://www.arduino.cc>

You should always have an Arduino Uno or an Arduino Leonardo at your disposal, along with a basic set of core electronics such as a breadboard, wires for prototyping, buttons, LEDs and a servomotor or two.

- [Arduino Leonardo](https://store.arduino.cc/arduino-leonardo-with-headers)
- [Arduino Uno](https://store.arduino.cc/arduino-uno-rev3)

There are many starter kits containing everything you need to get started (circuit + electronic components):

- [Elegoo Starter Kit](https://www.amazon.fr/Elegoo-Démarrage-dUtilisation-Débutants-Professionnels/dp/B01JD2Z5XW?ref_=ast_sto_dp)

If you already feel comfortable with the Arduino platform, and wish to have access to more advanced features such as wifi or bluetooth, you can opt instead for an ESP32-based microcontroller:

- ESP32 link

Download the Arduino software here:

<https://www.arduino.cc/en/software>

Arduino is simple software, so great for beginners. But you can also use VS Code (cf. above) to code your Arduino projects:

[Arduino extension](https://marketplace.visualstudio.com/items?itemName=vsciot-vscode.vscode-arduino) (VS Code)

### Shapr3D
If you have an iPad + Pencil, get Shapr3d. You won't regret it. It is easy to learn and is the fastest way to design CAD-style physical objects, and uses the same "Parasolid" 3D rendering engine as the industry CAD standard Solidworks, albeit without all the gazillion extra tools and solutions Solidworks provides. But for pure modelling of objects, gadgets, furniture, and all sorts of "stuff", Shapr3d is blazingly easy, fast, and feels like the future of CAD:

<https://www.shapr3d.com>

There is a free student + teacher license that allows you to work on more than two models at once. You have to renew this license every year:

<https://www.shapr3d.com/education>

### Rhino + Grasshopper
In the design world there used to be two main tools for making physical objects: Rhino & Solidworks. Recently Fusion 360 has been moving massively into this territory. Rhino, like Solidworks is a +20 year-old Computer-Assisted Design (CAD) software tool. Of the two, Rhino is a more creative and free-form shape-exploration tool, whereas Solidworks is more on the engineery-machine-part tool side of the fence.

<https://www.rhino3d.com>

There is a student/faculty price:

<https://www.rhino3d.com/en/sales/europe/>

Note: if you are on an M1-based Mac, Rhino currently runs in emulation mode. M1 emulation is insanely fast, so don't worry too much. There are currently still some bugs but it should be fine for most uses. You will have to wait for the next version of Rhino for full native M1 compatibility.

Grasshopper is visual, node-based plug-in that allows you to create parametric designs in Rhino. Imagine designing a chair, and then plugging various parameters of that design into a modular system that allows you to tweak the chair by sliding around visual sliders.

### Fusion 360
The up-and-coming beheamoth of CAD tool, with a whole suite of functionality that all works together.

- - -

## Machine Learning

### Runway ML
Runway is great tool for exploring machine learning through a well-designed user interface :

<https://runwayml.com>

We usually start teaching machine learning through Runway.

### ML5
ML5 is an offshoot of the P5 project, making it easy for beginning creative coders to download some of the latest and greatest machine language "models" and incorporate them into their sketches.

<http://ml5js.org>

It is probably best to get familiar with the basics of P5 first, before exploring ML5.

- - -

## Wireframing/Diagrams

### Miro
We use Miro to collaboratively flesh out ideas, make mindmaps, write story trees, design website navigation, and all sorts of other things.

<https://miro.com/>

### Figma + Bravo
Figma is one of many possible tools you can you to make interactive wireframes of an app or website.

<https://www.figma.com>

By adding Bravo into the mix, you can convert your Figma prototype into an actual working app that you can install onto your phone.

<https://www.bravostudio.app>
