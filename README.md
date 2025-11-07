# The Compiler for #C and C++

### Please check out: [WinLibs](https://winlibs.com/) for the latest build.

---

<br>

# I. Installation Link

### [Compiler MinGW latest version](https://github.com/brechtsanders/winlibs_mingw/releases/download/15.2.0posix-13.0.0-msvcrt-r1/winlibs-x86_64-posix-seh-gcc-15.2.0-mingw-w64msvcrt-13.0.0-r1.zip) (Auto-download)
More Information @ `github.com/brechtsanders`  
**Note:** Always check for the latest update!

---

# II. Step by Step:

---

## 1. The Path
- Extract `.zip`, create a `folder`, and copy `the folder path`.
- Example: `C:\<folder_name>`
  - (*`<folder_name>` - it means the custom folder with name you've created or choose the existing folder*).

## 2. Search on Search Bar or Control Panel
- **Search Bar**
  - Search "**Edit the system environment variables**" → click "**open**".
- **Control Panel**
  - Search "**System**" on **Control Panel** and find → click "**Edit the system environment variables**".
- Add the PATH environment variable.

## 3. **System Properties**
- Go to "**Advanced**" and find → click "**Environment Variables"**.

## 4. [→ Environment Variables]
- Look the "**System Variables**" and find → click "**Path**".
- **3 Options exist**: [New] [**→ Edit**] [Delete]

## 5. [→ Edit environment variable]
- Click "**New**" and paste the folder path where the extracted files from the ZIP are located.
- Example: `C:\<folder_name>\<extracted_folder_name>`
- **Done? All [→ OK]**

## 6. Configuration C/C++ on Visual Studio Code
- **Ctrl + Shift + P**
- Search and find "**C/C++: Edit Configurations (UI)**".
- **Enter** and **2 Options** exist:
  - **`select a detected compiler path`** from *the drop-down list*.
  - **`fill the compiler path`** with *specify path*.

## 7. Check the GCC (GNU Compiler Collection)
```
gcc --version
```

## 8. Create a File for #C and C++ File Extension
- Example:
  - `<file_name>.c` (**#C**)
  - `<file_name>.cpp` (**C++**)

## 9. Compile and run
### #C
```
gcc <file_name>.c -o <file_name>.exe
```
```
./<file_name>.exe
```

### C++
```
g++ <file_name>.cpp -o <file_name>.exe
```
```
./<file_name>.exe
```
### Note:
- `gcc` ← **Compiler for #C**
- `g++` ← **Compiler for C++**
- `<file\_name>.c` ← **#C File Extension**
- `<file\_name>.cpp` ← **C++ File Extension**
- `-o <file\_name>.exe` ← **Compiled Executable File**
  - `-o` ← **Output (tells the compiler what name to give the output file)**
  - `without -o` ← **create a default name file**
    - `a.exe` ← **(Windows)**
    - `a.out` ← **(MacOS/Linux)**
