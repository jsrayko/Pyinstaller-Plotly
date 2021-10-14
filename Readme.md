A few quick notes on compiling these programs using pyinstaller.
I used Python 3.6 and pyinstaller on windows 10.
Run requirements.bat  to pip install all of the packages I think you need (this may not be exhaustive)
use BuildApp.bat to compile the code.

You will need app.spec in this directory. It has a few lines that tell it where to find some libraries. 
You will need to update the location of those libraries, per the location of the code and your python installation.


Custom hooks don't appear to be necessary for either script


You need to install UPX and update the upx file location in buildApp.bat if you want the executables compressed 
I used the win64 version
https://github.com/upx/upx/releases/tag/v3.96



