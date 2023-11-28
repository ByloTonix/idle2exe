<h1 align="center">"Hack" for opening .py files by double-clicking.</h1>
<h4 align="center">By default .py files have an association with pythonw.exe, that makes it impossible to edit files of this format via IDLE without having to use right-click --> Edit with IDLE. Below is a "solution" that corrects this behavior.</h4>

## Solution:
- In the directory with Python installed, you need to find the directory **\Lib\idlelib**, which contains the file **idle.bat**. In it, you need to replace **CurrentDir** with direct paths to **pythonw.exe ** and **idle.pyw** (1st - in the folder **\Lib**, 2nd - in **\Lib\idlelib**).

To convert **.bat** to **.exe**, you can use the program from **[Tokyoneon](https://github.com/tokyoneon/B2E)**. The icon can be taken from **\Lib\idlelib\Icons**.
Using the above utility, we convert the edited **idle.bat** in **idle.exe**

## Usage:
- After creating the **.exe file**, save it in a convenient place and create a new association of .py files with this .exe (via "Open with" menu)
