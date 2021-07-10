# Interaction Design Tools
This is a list of some of the basic tools that any student of interaction design should have access to. This is very much a work-in-progress document and was principally designed for my students and colleagues at the [Master Media Design](https://www.hesge.ch/head/formations-recherche/master-en-media-design) and the needs of the larger community at the [HEAD – Genève](https://www.hesge.ch/head).

There is an infinite variety of possible tools that can be used in any project, so this list is by definition incomplete. These are just some of the current basic tools that should be downloaded/configured on your personal computer. Mastering one or two of these tools is a good idea. But just as importantly, learn to move from one to the other, depending on the needs of your projects. Do not get stuck in one single technical workflow.

This list is oriented more towards the *creative coding*, and/or the *make-stuff-break-stuff* approach, than the mockup *UX* or *UI* style of teaching interaction design.

Not everything here is open-source, although there are open-source alternatives listed, when available. Important student discounts, and/or free-versions exist for all of the paid tools listed here.

- - -

## Writing

Many projects begin with writing — either while finding the core poetics or mythology of a project, or directly as the central media of the project as in an interactive narrative (cf. below). Masters students also have to write a text-based thesis, and as such, choice of your writing tools is important. Although it is a university standard (especially for research documents), Microsoft Word and even LibreOffice are often the wrong tools for almost any interaction design document, media design thesis, or digital art & design research project.

### Markdown
[Markdown](https://fr.wikipedia.org/wiki/Markdown) gets it's own category.

Stop using Word for writing your documents. Use Markdown. You are welcome.

Markdown was originally designed for bloggers wishing to keep their text clean on their end (writer-oriented design tools), but with the possibility of easily converting said text into web pages with all the advantages that structured hypertext allows. From this original use-case, the simplicity and elegance of Markdown has allowed it to evolve into *the* de-facto, default format for all types of text documents: blogs, essays, chat discussions (cf. [Discord](https://support.discord.com/hc/en-us/articles/210298617-Markdown-Text-101-Chat-Formatting-Bold-Italic-Underline-)), documentation, and so on.

Markdown was designed to be easily transformed into whatever final format you need to export to: .doc, .txt, .html, .pdf, .epub, etc. (cf. Pandoc, below).

### Pandoc
By using a command-line tool (cf. Terminal, below) such as [Pandoc](https://pandoc.org), you can convert your Markdown texts to and from all sorts of formats: .doc, .otf, .pdf, .epub, etc.

1. [Install Pandoc](https://pandoc.org/installing.html) using the installer. Make sure to follow the instructions for adding LaTeX into your installation of Pandoc for whatever platform you are using. LaTeX will allow us to generate PDF files from Markdown
2. Create a simple Markdown text file (cf. [Getting Started](https://pandoc.org/getting-started.html)) in whatever text editor you prefer (cf. VS Code, below), and save it as `NameOfTextFile.md`
3. Open your Terminal (cf. below) into the folder of your text file
4. Type `pandoc NameOfTextFile.md -o NameOfTextFile.pdf`
	
Voilà, you now have a powerful workflow for writing your master's thesis. Here, for example, is [Mathilde Buenerd's Masters Thesis](https://github.com/mathildebuenerd/master-thesis-autocomplete) with instructions for the tools and workflow she designed to write and publish it.

Important note: in this Markdown > Pandoc > ________ approach, you will design the typography and layout using Cascading Style Sheets (CSS) — the format for designing web pages. This does not mean that your project is screen-based only; CSS can be used in print-based layout and typography.

- - -

## Storytelling

### Twine/Twee
Twine is a tool for making non-linear interactive text-based stories. It is a great tool for getting started with interactivity. At some stage of each narrative project, we almost always prototype at least some part of our interactive stories in Twine. Twine is the best and fastest way to learn interactive branching narrative.

<https://twinery.org>

Twine comes with a branching, node-based visual tool.

Once we have used Twine to quickly find our voice, we either move to another tool, such as Fungus (cf. below), or design a more sophisticated story using Twine itself, or its pure text-based variant, named Twee:

<https://www.motoslave.net/tweego/>

The best way to write text-only Twee stories is from within VS Code (cf. below).

### Bitsy
Bitsy is an even simpler tool than Twine to make interactive narratives, although in this case, the story format is that of a pixel-based adventure game. [Bitsy](https://ledoux.itch.io/bitsy)

### GB Studio
Another amazing open-source tool for interactive storytelling is GB Studio, which was designed for creating fully working interactive narratives on classic Gameboy and Gameboy Color consoles, but can also be exported directly for the web: [GB Studio](https://www.gbstudio.dev).

Following the invocation by [100 Rabbits](https://100r.co/site/home.html) to only use already-built technologies, GB Studio is a working solution for telling stories using both old and new hardware. If you integrate the webpage export into a native iOS or Android app wrapper, you can even distribute your story/game on a smartphone, tablet or smart TV.

### Fungus
Fungus is a free, open-source plug-in for Unity (cf. below) that you can download via the Unity Asset Store.

[Fungus](https://assetstore.unity.com/packages/tools/game-toolkits/fungus-34184)

It is an entirely visual node-based programming tool, meaning you can design interactions using a system of interconnected visual "blocks" instead of writing text-based code.

Fungus is a fun way to start learning Unity and works well for youth-workshop introductions to 2D game creation in Unity. With very little basic knowledge of Unity you can get a lot done with Fungus.

- - -

## Wireframing/Diagrams
One of the fastest ways to get started designing app-based or web-based interactions is to make a wireframe diagram of the flow of interactions.

### Miro
We use Miro to collaboratively flesh out ideas, make mindmaps, write story trees, design website navigation, and all sorts of other things.

<https://miro.com/>

### Figma
Figma is one of many possible tools you can use to make interactive wireframes of an app or website. [XD](https://www.adobe.com/fr/products/xd.html) is another option.

<https://www.figma.com>

### Bravo
By adding Bravo into the mix, you can convert your Figma prototype into an actual working app that you can install onto your phone.

<https://www.bravostudio.app>

Note: I have not tested this solution sufficiently to recommend it.

- - -

## Code
Code is probably the most important "tool" to learn when aquiring your basic interaction design skills, and for many the hardest. When we say "code", we mean text typed into some sort of "interpreter" or "compiler" that make your things do things. You can successfully design many projects using off-the-shelf solutions, or opt for visual node-based solutions such as Twine, Max, Fungus, etc. But probably, at some point, you will need to understand the rudimentary basics of text-based coding to create more unique experiences and especially if you want or need to build your own tools for your practice.

Warning: there is no silver-bullet one-language-to-rule-them-all. If someone tells you that they have discovered such a unique unicorn, they are most definitely wrong. Chances are they discovered a curious animal in the coding wilderness, found a way to tame it for their own needs, and are now extrapolating their own knowledge subset to the larger set of all other needs.

### VS Code
Visual Studio Code is an open-source code editor, maintained by big old Microsoft. You can use it to access/code/talk to all sorts of software, languages, and machines. You can use it to make websites, program an Arduino microcontroller, control a Raspberry PI, code a game in Unity, write Twine poetry, draw P5 sketches, write a masters thesis, and gazillion other things. It is currently the de-facto tool for coding stuff in general.

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
- [vscode-pandoc](https://marketplace.visualstudio.com/items?itemName=DougFinke.vscode-pandoc) (requires Pandoc installation, cf. above)

To make Unity (cf. below) work with VS Code, you should install the following :
- [Dot Net Core SDK](https://dotnet.microsoft.com/download)
- **For macOS users**, downlad the latest [Mono](https://www.mono-project.com/download/stable/) installer
- [C# Extension](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csharp)
- [Unity Debugger Extension](https://marketplace.visualstudio.com/items?itemName=Unity.unity-debug) (optional)
- [Unity Snippets Extension](https://marketplace.visualstudio.com/items?itemName=kleber-swf.unity-code-snippets) (optional)

If after all that you are still having problems reading your Unity scripts in VS Code, or cannot use the handy autocomplete features, read the following Microsoft document: [Unity Development with VS Code](https://code.visualstudio.com/docs/other/unity).

### Terminal
You should know where the Terminal is on your computer.

- macOS: `cmd` + `space` and type `Terminal`
- Windows: 
- Linux: 

Common commands from within the terminal are: `cd` change directory, `ls` list files in current directory, `mkdir` make directory, `cp` copy file, `mv` move or rename a file/directory.

The terminal is powerful. Be careful: you can break things.

### Package Manager
If you need to install commands in your terminal, you should use a "package manager". This will take care of a lot of the ugly details of installing and updating various commands that can be invoked directly from your terminal. For example, if you want to install Pandoc (cf. below), you can directly install it via a package manager such as `brew` or `apt-get` via the command line.

- macOS
	- install `brew`
- Linux (Ubuntu, Raspberry OS)
	- `apt-get`
- Windows
	- ???

### GIT
We use Git to backup, collaborate, and create historical breadcrumbs of our work.

*Why is this important?* You will **always** make mistakes, and by constantly creating backups of your work via Git, you can easily return to a previous version before your latest bender, high as a kite where you had an awesomesauce revolutionary idea that totally broke everything you had built up to that point; calm down; deep breath; pour yourself a tea; move back to a previous `git commit` from when you were more sober; get back to work making your awesome thing.

Make sure Git is installed on your machine. Open a Terminal (cf. above) and type `git` from the command line. You should see a list of possible Git functions.

To save your Git backups online, open free accounts on the two following websites:

- <https://bitbucket.org>
- <https://github.com>

You will share code from your various projects and download code from various contributors via these two websites, as well as other popular Git hosting sites.

- - -

## Languages

## HTML/CSS
Webpage design is usually the starting point for many designers just learning to code. Although it has some "programming language" aspects, HTML (HyperText Markup Language) is more of a description of layout, typography, and other design choices of a webpage. Basically, HTML describes the content and layout of a page, while CSS (Cascading Style Sheets) describes the visual design of the page and also can be used to animate elements on the page.

Although HTML and CSS were designed principally for publishing websites, there are aspects of CSS that were designed for print-based solutions. In other words, you can design your page to look one way when viewed through a browser, and entirely differently when printed or exported as a PDF, including handling of page breaks and other print-specific design choices. In the Media Design Master, many of us use a combination of Markdown (cf. below) + CSS + Pandoc as a replacement for designing a book or multipage document in InDesign.

## Javascript



## Python
Install a Python Virtual Environment.

```
// TODO
```

Install the latest Python version to your virtual environment.

```
// TODO
```

Install the Python package manager `pip3`

```
// TODO
```

Since we do a lot of A.I. experiments, be sure you have the following base Python packages installed:

- [Pytorch](https://pytorch.org/get-started/locally/)
- [Numpy](https://numpy.org/install/)
- [Tensorflow](https://www.tensorflow.org/install/pip?hl=fr)

## C#

C# is a language designed by Microsoft, and is used in many different fields; but for our uses is almost solely used in projects built in Unity (cf. below).

- - -

## 2D Graphics

### P5
P5 is the JavaScript evolution of the [Processing](http://processing.org) project and is essential for learning the basics of *creative coding*.

<https://p5js.org>

You can write P5 "sketches" using the `P5.vscode` extension for VS Code (cf. above). Or you can code your sketches directly inside the online P5 editor, which is handy for quickly prototyping any idea from whatever machine you are on: just open a browser, sign in, and starting coding an interactive sketch:

<https://editor.p5js.org>

Make sure you create an account in order to save your work and access your previous sketches.

*Advanced users:* if you are already experienced in creating web pages, you can download the latest "complete library" version of P5 to your computer. This will also allow you to code offline. In this approach, you would write your P5 sketches using VS Code (cf. above):

<https://p5js.org/download/>

## Paper.js
P5.js is very much a pixel-based solution for coding images; if instead you want a vector-first solution, [Paper.js](http://paperjs.org) was designed first and formost as a designer-oriented vector-based tool for people who code in Javascript. Paper.js was designed and developed by our colleague [Jürg Lehni](http://juerglehni.com), along with another brilliant designer, [Jonathan Puckey](https://puckey.studio).

## Drawbot

If you are a graphic designer and want to explore coding tools built directly for/by designers, you should try [Drawbot](https://www.drawbot.com). Drawbot is similar to Processing/P5.js, in that it was designed as a simple environment to not only explore creative coding, but also to learn coding itself. The list of instructions is simple but powerful, and can be used either with its simplified all-in-one integrated [Drawbot App](https://www.drawbot.com/content/drawBotApp.html) interface, or via VS Code.

Warning: this is a macOS-only solution.

- Download [Drawbot](https://www.drawbot.com/content/download.html) for Mac OS X
- Instructions for integrating Drawbot into VSCode: [drawbot-vscode](https://github.com/arrowtype/drawbot-vscode)
- [Roberto Arista](http://projects.robertoarista.it)'s excellent tutorial [Python For Designers](https://pythonfordesigners.com) should give you all the basics you need to get started

## Robofont
If you also want to use the Python language to design your own fonts, the natural font designer's complement to Drawbot is [Robofont](https://robofont.com). Much like its competitors Glyphs or FontForge, Robofont has a graphical interface for designing your glyphs. But it was also designed with scripting window (the same as Drawbot, by the way) where you can code different parameters and shapes using Python instructions. Although you can use Robofont only through its graphical interface, in many senses, the tool was built around extensibility via code.

## Glyphs
[Glyphs](http://glyphsapp.com) is also an excellent font editor and has an excellent workflow for creating variable fonts, to give just one example. Like Robofont, you can code changes to your fonts, or even generate forms, using Python from within the app. You can also write your own plugins to Glyphs using Python. Cf. [Add your own Python code for pretty much anything](https://glyphsapp.com/features#code)

- - -

## 3D

## Unity
Unity is a "game engine", used for making 3D games or interactive experiences in general. Unity projects can be distributed on Mac, PC, Linux, Web, iOS, iPadOS, Android, Switch, Playstation, & XBox. It is the de-facto standard for AR, and is the dominant player in the world of VR. It's closest competitor is the Unreal Engine, or the more modest open-source project Godot.

Start by creating a free account on the Unity website:

<https://id.unity.com/account/new>

You can use any one of the free tiers, either student or free. There is no need for you to sign up for a "pro" account.

Always install whichever version of Unity you prefer via the "Unity Hub".

<https://unity3d.com/fr/get-unity/download>

Important: **Ignore the "Choose your version of Unity" button** and instead install your preferred version of Unity directy from within this "Unity Hub". It will allow you to add and/or remove the various (large) components of your Unity installation at a later date, depending on the platform(s) you are targetting.

Open Unity Hub on your computer and login to your account. From this hub, download the latest `LTS` version of Unity. `LTS` is the "Long Term Support" version of Unity and will last for at least two-years, i.e. the length of a masters programme. Currently we are using Unity 2020.3.x. The last number is just bug fixes and is compatible with any other 2020.3.x release.

*Special note:* constantly, always, without fail, someone will ask: "Isn't Unreal better than Unity?", "I read that Unreal is better than Unity", or "But I saw this YouTube video that says...", and so on. So: *tell me*, is it better? Yes, if you insist. But also: no, it isn't. Or, maybe. Or, whatever. Ask someone else. It's usually the wrong question. Unreal is not "better". It is "different", even if there is an overlap and they are definitely competitors. Unreal is awesome for cinematic immersive 3D world explorations. The latest Meta Human stuff is incredible, but Character Creator 3 works with Unity, so maybe it isn't that incredible after all. We'll see. Again, wrong question. Some people think it's easier to learn Unreal; many people think it's actually harder. All those people are right or wrong, depending on who you ask. We use Uniy for a bunch of stuff Unreal doesn't doesn't do as well. Does that make Unity better than Unreal? No. Next question. *What? You want a better answer? Hmmmm… Unity is ok to good for *some* of the things Unreal does really well, but is usually better for our needs because it does everything else, especially if you want to make 2D interactive games or experiences. But for 2D game design you can find a gazillion other alternatives. And there is always Godot, and even the cool 2D-oriented [P5.Play](https://molleindustria.github.io/p5.play/) plugin for P5 by none other than the amazingly-awesome [Molleindustria](http://www.molleindustria.org). So, final word: I don't know. Maybe you should ask better questions.

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

### ML-Agents
During the second semester Media Design 2020-21 session, we started exploring [ML-Agents](https://github.com/Unity-Technologies/ml-agents), a Unity + pytorch solution for using Unity to make [Karl Sims](https://www.karlsims.com)-like virtual creatures and interactive objects and games. This is a powerful design tool for speculative urbanism, experimental game design, and all sorts of other uses. People also use it [to train cars](https://unity3d.com/simulated-environments-for-autonomous-vehicle-training) not to kill (too many of) us.

<https://github.com/Unity-Technologies/ml-agents>

We are currently writing an online tutorial for using this library, based on our experimentations.

Note: this library for Unity requires 1. a basic understanding of Unity and 2. a basic understanding of programming C# scripts for Unity.

- - -

## Web

### Website
There are a gazillion solutions for making a website. There are also services like Squarespace, WordPress, or Adobe Portfolio for making a website via a drag-and-drop interface.

### Kirby
Kirby is a solution for making websites that is based off of an extremely clean, well-designed-and-engineered minimalist approach to handling modular content, design, and interaction. It is a "flat", file-based solution, i.e. it does not require the installation of a database; instead it builds your website out of a simple collection of folders containing sub-folders and files in those folders. If you know how to make a folder and put files into folders, you know how to make websites using Kirby.

[Kirby](https://getkirby.com)

### Web App
A fast way to make an app is to build a web page and then to build an app around it, and install that app onto your iPhone, iPad, or Android phone/tablet.

Many of the creative coding tools here generate [HTML5](https://fr.wikipedia.org/wiki/HTML5) webpages: Twine narratives, P5 interactive/generative sketches, etc. 

Here is a tutorial for [Creating a WebView App in XCode](https://www.youtube.com/watch?v=zm9g7hPESz8). This is an iOS/macOS-only solution. The idea is to create a local folder containing your P5 sketch or Twine story's index.html file and associated assets (images, sounds, whatever), then to create an app around that folder in xCode.

- Todo: add Android .apk webapp solution.
