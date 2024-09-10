# Getting Started Editing Files

* First, we’re talking about text-only editors like Notepad. Not word processors like Word. 
	* The reason we’re only talking about text editors is because that’s what you need to code with or to write a git commit message.
* On your local desktop installation
	* A couple of cross-platform GUI editors are out there, most notably Visual Studio Code, but also Sublime Text.
	* There are editors specific to your distribution, for instance KDE has Kate
	* These are great for local use, but the scenario where we encounter the unfamiliar is when we are trying to edit text on a remote computer.  We need an editor that is available on any remote system without you installing it and runs inside the terminal. This is the kind of editor you’ll use for Git, for editing system configuration files when you first set up a machine, and for editing code.  Usually connecting to such a machine you get what you get.  The editor in its completely default state with no configuration.
* Two famous and popular editors meet this criteria: Vim and nano. (Emacs is rarely installed by default). In all the criteria I just named, yes, these two editors are alike; but beyond that they couldn’t be more different.
	* The main differences
		* nano is simple to use and easy to learn; Vim is complicated: it has many more features, takes longer to learn, and even has its own complete language.  Anybody can use nano.  You've got to _want_ to use Vim.
		* nano is modeless: you're always typing content; Vim is modal: typing means different things in different modes
* Let's start with Vim <live demo here>
	* vim <filename>     the file does not have to exist, Vim will create it when you first save
	* you start in normal mode... typing means commands.  Hit 'i' to go into insert mode.  Now you're typing into your document.  In insert mode the arrow keys work, and so does backspace.
	* Esc gets you back to normal mode
	* from normal mode, you can type on Vim's command line by starting with a ':'.
	* to save your document, from normal mode type ':w' which issues the command to "write" your document.  To quit ':q'.  You can combine these ':wq'.  And to throw away your changes, quit without writing ':q!'
	* there are two very good sources of help: instead of running vim, you can run vimtutor which is a half-hour introduction to using vim.  You should definitely start here.
	* the other is the ':help' command (from normal mode).  By itself, it starts at the contents of the user manual; but you can get help on anything, the top-level :help tells you how
	* there's a lot more to Vim and we've done whole meetings on it.  You can see previous videow.
	* I love Vim, but I want to discourage you from starting with it.  If you're a beginner with Unix/Linux, start with nano.  Attack Vim later, when you've got more experience.
* Now nano <live demo here>
	* nano <filename>    the file does not have to exist, nano will create it when you first save
	* you are immediately typing content.
	* the bottom two lines of the screen show a list of the most common commands.  The caret means the control key.  The very first one is Ctrl-G.  That goes to the help page that shows you all the keystrokes.
	* to save your document, type Ctrl-O
	* to quit type Ctrl-X