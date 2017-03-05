Quick and Dirty; C/C++ from Zero with Visual Studio Code on OSX
===
Things:
1. F5 for breakpoint debugging.
2. ⌘+B to build an executable.
3. launch.json with example command line arguments and environment variables.

Installing c/c++ breakpoint debugging and intellisense.
---
1. Install Command Line Tools from Terminal.
```
    $ xcode-select --install
    # at install confirmation, click "Install"
```
2. Install Visual Studio Code (VSC).
```
    https://code.visualstudio.com
```
3. Open VSC and install debugging extension.
```
    ⌘+P > ext install cpptools
    # details at C/C++ by Microsoft
    # https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools
```
4. Open VSC and install intellisense extension.
```
    ⌘+P > ext install vscode-clang
    # details at C/C++ Clang Command Adapter by Yasuaki MITANI
    # https://marketplace.visualstudio.com/items?itemName=mitaki28.vscode-clang
```

VSC Configuration Notes:

1. Task Runner Configuration
```
    ⌘+P > ext configure task
    # creates tasks.json
```
2. Build Configuration
```
    ⌘+P > edit configuration
    # creates c_cpp_properties.json
```
3. Debugging Configuration.
```
    ⌘+P > open launch
    # creates launch.json
```
VSC C/C++ configuration details at https://code.visualstudio.com/docs/languages/cpp
---

Mac Configuration Notes:
1. reclaim f-keys
```
    ⌘+space > preferences
    # open Keyboard
    # check "use all f-keys as standard".
```
2. reclaim more f-keys
```
    ⌘+space > preferences
    # open Mission Control
    # change "Show Desktop" keyboard shortcut
    # chang "Show Dashboard" keyboard shortcut
```