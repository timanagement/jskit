# JavaScriptCore Kit (JSKit) 

Cross-platform JavaScript framework for Delphi. Evaluate JavaScript programs from within a Delphi app, and support JavaScript scripting of your Delphi app.

![MacOS](Screenshots/macos.png)
![Linux](Screenshots/linux.png)
![Win](Screenshots/win.png)

# Overview

The JSKit allows you to evaluate JavaScript programs from within an Delphi program using JavaScriptCore. It also lets you insert custom objects to the JavaScript environment.

# Features

* Implicit export Delphi object instance with all public or published properties and methods to script.
* Evaluate component's event from JavaScript
* Call JavaScript function from Delphi
* Wrap anonimous procedure to JavaScript function
* Create new instances of Delphi object from JavaScript

# Distribution

Windows JSKit's application requires JavaScripCore shared library. All required DLL located at Redist folder. 

macOS already has JavaScriptCore.

JavaScriptCore on Linux can be installed by "sudo apt install libwebkitgtk-3.0"

# Requirements

Windows version works with Delphi version since Delphi Seattle. MacOS and Linux version requires CrossVcl from http://www.crossvcl.com

# License

Remember that this library and its source code are distributed under terms of Mozilla Public License (MPL) version 2.0. By using this product, you acknowledge your consent to be bound by the terms of MPL.

If you need to use this framework for a project with a different licensing requirements, feel free to contact the author for more options.

Copyright (c) 2017 Eugene Kryukov

http://www.ksdev.com