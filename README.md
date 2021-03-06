# BatchCMD
A package with batch commands I created in order to make my (and of course yours) easier and which will slowly expand.
It works on any Windows OSs.

This package contains the following programs:
-   **init.bat**: a good initiative to start working on Command Prompt (Window's CLI: cmd.exe) especially when using several instances of it that are used for different tasks.
-   **javam.bat**: If you develop Java based programs without necessarily using IDEs then this tool is the one that will save you the time taken to type the basic stuff in the code such as public static ... main(), also being able to create a class and a test program for it in a few seconds.
-   **htm.bat**: Same as javam but for HTML pages.
-   **pdm.bat**: Same as javam but for Processing java programs (PDE files)
-   **rev.bat**: If you're into reviewing websites (or simply webpages) like me than this tool will generate a ready file for you (even in markdown, and perhaps soon in XML or close to it).
-   **batm.bat**: A batch script maker that also allows you to create a command file (just like all the ones of this package).
-   **multi.bat** (currently in progress): Same as **init.bat** but mutli cmd instance.
-   **arch.bat**: 3rd-partyless directory archiver.
-   **unarch.bat**: the opposite of the arch
-   **tran.bat**: Directory transformer which transfer everything of that folder into an image.
-   **mrd.bat** (*coming soon*): Random decimal file maker
-   **update.bat**: A program/software updater that copy-paste the programs/sofwares of your dev/download directory into the System32.
-   **php.bat**: Same as htm but for PHP scripts.

The executables can be found here:
-   **init.exe** (Win64/Win32): http://adf.ly/1Xq4am / http://adf.ly/1Xq5Hi
-   **javam.exe** (Win64/Win32): http://adf.ly/1Xq4cu / http://adf.ly/1Xq5KW
-   **htm.exe** (Win64/Win32): http://adf.ly/1Xq4eP / http://adf.ly/1Xq5DH
-   **pdm.exe** (Win64/Win32): http://adf.ly/1Xq4hr / http://adf.ly/1Xq5Mh
-   **batm.exe** (Win64/Win32): http://adf.ly/1Xq4jx / http://adf.ly/1Xq58y
-   **multi.exe** (Win64/Win32): / 
-   **arch.exe** (Win64/Win32): http://adf.ly/1Xq4m0 / http://adf.ly/1Xq520
-   **unarch.exe** (Win64/Win32): http://adf.ly/1XuLx4 / http://adf.ly/1XuM0w
-   **tran.exe** (Win64/Win32): http://adf.ly/1Xq4nx / http://adf.ly/1Xq5SS
-   **mrd.exe** (Win64/Win32): / 
-   **update.exe** (Win64/Win32): http://adf.ly/1XuFqO / http://adf.ly/1XuGkd
-   **php.exe** (Win64/Win32): http://adf.ly/1ZKDVO / http://adf.ly/1ZKDil

Once the executable/batch script are in the right place, type [command] /? to see their respective documentation.

Some ideas:
-   Compiler (.rev->rtf/docx/html+reading software, .hex/.bin/.b64->ascii) with a linter
-   Package installer (unzip and move the executables): a sub-optimal way of doing this is:
    unarch mypackage.zip mypackage
    update mypackage exe *(if the package doesn't have executables than change exe to a more appropriate extension)*
-   GitHub deployer
