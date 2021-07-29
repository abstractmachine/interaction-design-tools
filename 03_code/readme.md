## Code
Code is probably the most important "tool" to learn when aquiring your basic interaction design skills, and for many the hardest. When we say "code", we mean text typed into some sort of "interpreter" or "compiler" that make your things do things. You can successfully design many projects using off-the-shelf solutions, or opt for visual node-based solutions such as Twine, Max, Fungus, etc. But probably, at some point, you will need to understand the rudimentary basics of text-based coding to create more unique experiences and especially if you want or need to build your own tools for your practice.

Warning: there is no silver-bullet one-language-to-rule-them-all. If someone tells you that they have discovered such a unique unicorn, they are most definitely wrong. Chances are they discovered a curious animal in the coding wilderness, found a way to tame it for their own needs, and are now extrapolating their own knowledge subset to the larger set of all other needs.

### VS Code
Visual Studio Code is an open-source code editor, maintained by big old Microsoft. You can use it to access/code/talk to all sorts of software, languages, and machines. You can use it to make websites, program an Arduino microcontroller, control a Raspberry PI, code a game in Unity, write Twine poetry, draw P5 sketches, write a masters thesis, and gazillion other things. It is currently the de-facto tool for coding stuff in general.

<https://code.visualstudio.com/download>

Once you have downloaded and installed VS Code on your machine, you should install the following "exensions" to VS Code: `Menu` > `View` > `Extensions`

- [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
- [Live Share](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare)
- [p5.vscode](https://marketplace.visualstudio.com/items?itemName=samplavigne.p5-vscode) (cf. (tutorial:P5 link:tools/2d-graphics))
- [Python for Visual Studio](https://marketplace.visualstudio.com/items?itemName=ms-python.python)
- [Arduino extension](https://marketplace.visualstudio.com/items?itemName=vsciot-vscode.vscode-arduino) (cf. (tutorial:Arduino link:tools/electronics))
- [GIT Lens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens) (cf. (tutorial:Git link:tools/code))
- [SSH Tools](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-ssh)
- [Twee 3 Language Tools](https://marketplace.visualstudio.com/items?itemName=cyrusfirheir.twee3-language-tools) (cf. (tutorial:Twine-Twee link:tools/storytelling))
- [vscode-pandoc](https://marketplace.visualstudio.com/items?itemName=DougFinke.vscode-pandoc) (requires Pandoc installation, cf. above)

To make (tutorial:Unity link:tools/3d-grapghics) work with VS Code, you should install the following :
- [Dot Net Core SDK](https://dotnet.microsoft.com/download)
- **For macOS users**, downlad the latest [Mono](https://www.mono-project.com/download/stable/) installer
- [C# Extension](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csharp)
- [Unity Debugger Extension](https://marketplace.visualstudio.com/items?itemName=Unity.unity-debug) (optional)
- [Unity Snippets Extension](https://marketplace.visualstudio.com/items?itemName=kleber-swf.unity-code-snippets) (optional)

In Unity's preferences, set the development tool via `Unity` > `External Tools` > `External Script Editor` > `Browse` and point it to your `Visual Studio Code` installation on your computer.

If after all that you are still having problems reading your Unity scripts in VS Code, or cannot use the handy autocomplete features, read the following Microsoft document: [Unity Development with VS Code](https://code.visualstudio.com/docs/other/unity).

### Terminal
You should know where the Terminal is on your computer.

- macOS: `cmd` + `space` and type `Terminal`
- Windows: 
- Linux: 

Common commands from within the terminal are: `cd` change directory, `ls` list files in current directory, `mkdir` make directory, `cp` copy file, `mv` move or rename a file/directory.

The terminal is powerful. Be careful: you can break things. You can even break your operating system, requiring you to re-install it from scratch. *Of course this has **never never ever** happened to us, but we just wanted to warn you.*

### Package Manager
If you need to install commands in your terminal, you should use a "package manager". This will take care of a lot of the ugly details of installing and updating various commands that can be invoked directly from your terminal. For example, if you want to install Pandoc (cf. above), you can directly install it via a package manager such as `brew` or `apt-get` via the command line.

- macOS
	- install `brew`
- Linux (Ubuntu, Raspberry OS)
	- `apt-get`
- Windows
	- ???

### GIT
We use Git to backup, collaborate, and create historical breadcrumbs of our work.

*Why is this important?* You will **always** make mistakes, and by constantly creating backups of your work via Git, you can easily return to a previous version. The story goes more or less like this:

> You are making the greatest thing ever made. High as a kite on your latest bender full of inspiration and manic glee, you have an awesomesauce revolutionary idea that totally breaks everything you had built up to that point. Calm down. Deep breath. Go for a walk. Pour yourself some tea. We cool, because you use git to breadcrumb your work. Just move back to a previous `git commit` from when you were more sober, and get back to work making your awesome bestest thingy ever.

Make sure Git is installed on your machine. Open a Terminal (cf. above) and type `git` from the command line. You should see a list of possible Git functions.

To save your Git backups online, open free accounts on the two following websites:

- <https://bitbucket.org>
- <https://github.com>

You will share code from your various projects and download code from various contributors via these two websites, as well as other popular Git hosting sites.
