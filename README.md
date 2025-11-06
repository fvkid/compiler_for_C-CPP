# The Compiler for #C and C++
---
<br>

# I. Installation Link
---
## → [compiler MinGW latest version](https://github.com/brechtsanders/winlibs_mingw/releases/download/15.2.0posix-13.0.0-msvcrt-r1/winlibs-x86_64-posix-seh-gcc-15.2.0-mingw-w64msvcrt-13.0.0-r1.zip) – [Brecht Sanders](https://github.com/brechtsanders/)
<br>

# II. Step by Step:
---
<br>

## 1. The Path
- Extract **.zip**, create a **folder**, and copy **the folder path**.
- Example: C:\\<**folder_name**> (*<folder_name> - it means the custom folder with name you've created or choose the existing folder*).
<br>

## 2. Search on Search Bar or Control Panel
- Search and open "**Edit the system environment variables**".
- Search "**System**" on **Control Panel** and find "**Edit the system environment variables**".
- Add the PATH environment variable.
<br>

## 3. **System Properties** <br>
- Go to "**Advanced**" and find → click "**Environment Variables"**.
<br>

## 4. [→ Environment Variables] <br>
- Look the "**System Variables**" and find → click "**Path**". <br>
- **3 Options exist**: [New] [**→ Edit**] [Delete]
<br>

## 5. [→ Edit environment variable] <br>
- Click "**New**" and paste the folder path where the extracted files from the ZIP are located. <br>
- Example: C:\\<**folder_name**>\\<**extracted_file_name**> <br>
- **Done? All [→ OK]**
<br>

## 6. Configuration C/C++ on Visual Studio Code <br>

- **Ctrl + Shift + P** <br> 
- Search and find "**C/C++: Edit Configurations (UI)**". <br>
- **Enter** and **2 Options** exist: <br> 1. select a **detected compiler path** from *the drop-down list*. <br> 2. **fill the compiler path** with your *specify path*.
<br>

## 7. Check the GCC (GNU Compiler Collection) <br>
```
gcc --version
```
<br>

## 8. Compile and run test <br>
```
Create a file for #C and C++ File Extension
Example:
<file_name>.c
<file_name>.cpp
```

<br>

## 9. Run on the Terminal <br>
```
gcc <file_name>.c -o <file_name>.exe
./<file_name>.exe
```
```
g++ <file_name>.cpp -o <file_name>.exe
./<file_name>.exe
```

### Note:
- gcc ▸ **Compiler for #C**
- g++ ▸ **Compiler for C++**
- <file\_name>.c ▸ **#C File Extension**
- <file\_name>.cpp ▸ **C++ File Extension**
- -o <file\_name>.exe ▸ **Executable File < Compile Result**


