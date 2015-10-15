About
=====
This is a TextMate/Sublime/VS Code/Atom bundle providing language support for x86_64 assembly language in a variety of dialects (nasm/yasm/tasm/gas).

Features
========
* Basic support for NASM/YASM/TASM/GAS syntaxes
* Most up-to-date instruction sets:
  * Legacy/undocumented registers and instructions
  * FPU/MMX/3DNow!
  * SSE/SSE2/(S)SSE3/SSE4/SSE4.1/SSE4.2/SSE4.a
  * AVX/AVX2/AVX512, including pseudo-ops
  * AES-NI/SHA
  * VMX/SMX/NPX/SGX
  * other AMD/Cyrix/VIA and planned future Intel extensions

Source code
===========
The latest version of this package should be available on [GitHub](https://github.com/13xforever/x86-assembly-textmate-bundle).

To compile the yaml sources to tmLanguage, you'll need [AAAPackageDev](https://packagecontrol.io/packages/AAAPackageDev). 
More information and a user guide is available on the [project page](https://github.com/SublimeText/AAAPackageDev).

Atom [import guide](https://atom.io/docs/latest/hacking-atom-converting-from-textmate).

VS Code [import guide](https://code.visualstudio.com/updates/#_customization-adding-language-colorization-bracket-matching) (no IntelliSense support though)!

Contributors
============
[YASM tests](Tests/yasm-regression) are provided by [yasm-regression](https://github.com/yasm/yasm-regression) project.

Examples
========
* Sublime Text with Monokai Extended Bright color scheme
  ![Sublime Text with Monokai Extended Bright color scheme](https://github.com/13xforever/x86-assembly-textmate-bundle/blob/master/Screenshots/Sublime%20Text%203%20-%20Monokai%20Extended%20Bright.png?raw=true)
* Atom with One Dark syntax theme
  ![Atom with One Dark syntax theme](https://github.com/13xforever/x86-assembly-textmate-bundle/blob/master/Screenshots/Atom%20-%20One%20Dark.png?raw=true)
* Visual Studio Code with default Dark color theme
  ![Visual Studio Code with default Dark color theme](https://github.com/13xforever/x86-assembly-textmate-bundle/blob/master/Screenshots/Visual%20Studio%20Code%20-%20Dark.png?raw=true)
