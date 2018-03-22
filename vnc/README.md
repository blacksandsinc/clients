From command prompt execute the following, A fast way to launch this window is to press the Win + R keys on your keyboard. Then, type cmd

First extraxt VNC.zip in your download directory, then follow the rest if instructions from the command line.
```bash
cd %HOMEPATH%/Downloads
# Unzip VNC.zip Downloaded Package
cd VNC
UltraVNC_1_2_12_X64_Setup.exe /SP- /VERYSILENT /NORESTART /LOADINF=setup.ini
copy ultravnc.ini "C:\Program Files\UltraVNC\ultravnc.ini"
cd "C:\Program Files\UltraVNC"
winvnc.exe -install
winvnc.exe
```
