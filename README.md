# vs-code-cpp
My vs code example configuration for coding c/c++ on Windows

## Downloads
### Downlaod VS Code
- Download [VS Code](https://code.visualstudio.com) ofcourse.

### C/C++ Compiler & GDB
- [Download MSYS2](https://www.msys2.org)
- Open the msys terminal and type `pacman -S mingw-w64-x86_64-gcc mingw-w64-x86_64-gdb --noconfirm`.

### LLVM (clang-format)
- Get LLVM-*.*.*-win64.exe from the releases page from [here](https://github.com/llvm/llvm-project)


## Configuration
### Add Environment Path
Add the following paths:
- `C:\msys64\mingw64\bin`
- `C:\Program Files\LLVM\bin`

### VS Code Configuration 
#### Install Extensions
Besides using the configuration provided in this repository, you (probably) need the following extensions
- C/C++
- C/C++ Compile Run (alt. Code Runner)
- C/C++ Extension Pack
- CLang-Format
- clangd

#### Intellisense
- When installing clangd, you'll get prompt whether to install clangd, hit install.
- Use the key combination `Ctrl + Alt + F` to trigger auto format, choose clang-format if prompt.


## Other note(s)
The clang-format is from [Google](https://github.com/kehanXue/google-style-clang-format) but the `IndentWidth` changed to 4.
