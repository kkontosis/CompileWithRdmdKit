CompileWithRdmdKit for Sublime Text
--------------------------

CompileWithRdmdKit adds some tools for D language in Sublime Text 3.
It is meant to be used alongside DKit.

It provides an alternative build system script, that focuses on single file execution and unit tests.

In order to use, select `rdmd` as the Build System, from the Tools menu.

Before running
--------------

* The D language packages are a prerequisite.
* Optionally install the [DKit package](https://github.com/yazd/DKit)
* The utlility rdmd needs to be symlinked to the global path. If not try: `brew tap kkontosis/brew && brew install rdmd`

Installation
------------

To install, clone this repository into your Sublime Text packages folder.
You can find where your folder is located by clicking on 'Preferences -> Browse Packages'. Probable places:
    * Linux - `~/.config/sublime-text-3/Packages/`
    * Windows - `sublime-text-3\Data\Packages`
    * Mac OSX - `~/Library/Application Support/Sublime Text 3/Packages`
