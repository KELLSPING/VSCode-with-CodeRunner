# VSCode-with-CodeRunner #

## Outline ##

* [Dev Env](#dev-env)
* [Notes](#notes)
* [Learning Target](#learning-target)

## Dev Env ##

* Package Manager: Chocolatey
  * VSCode
  * MinGW-w64 12.2.0
  * PowerShell core 7

* OS
  * Windows 11

* VSCode Extension
  * C/C++, C/C++ Extension Pack, C/C++ Themes
  * Code Runner

## Notes ##

* Code Runner can only use for compile and run the code, it can not debug the code.

* Two ways to compiler the code.
  * Use "C/C++"
    1. Run C/C++ File
    2. Debug C/C++ File

  * Use "Code Runner"
    1. Run Code

* Setup in the VSCode
  * tasks.json : Used to define tasks for building, which includes compiling and linking programs.
  * launch.json : Used to configure the debugging env, such as the debugger (gdb), executable file path, etc.
  * settings.json : Configures file for the VSCode editor that stores various editor settings. For this case, it used to configure the code runner.

* Variables Reference in VSCode
  * Link : [Variables Reference](https://code.visualstudio.com/docs/editor/variables-reference)
  * Predefined variables
    * ${cwd}
    * ${workspaceFolder}
    * ${file}
    * ${fileDirname}
    * ${fileBasenameNoExtension}

## Learning Target ##

* learning curve
  1. CodeRunner-test1 : Use Code Runner to compile and generate .exe file.

  2. CodeRunner-test2 : Use Code Runner to compile multi .c files and generate .exe file.

  3. CodeRunner-test3 : Use Code Runner to compile multi .c files and generate .exe file to specified location.

  4. CodeRunner-test4 : Use Code Runner to compile specified location multi .c files and generate .exe file to specified location.
