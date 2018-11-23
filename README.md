# gsudo (GUI sudo)
gksu/gksudo alternative for debian based distros, nothing fancy
# Installation
```
git clone git@github.com:st4s1k/gsudo.git &&
cd gsudo &&
chmod +x gsudo_installer &&
bash ./gsudo_installer
```
1. Copy-paste this command into the terminal.
2. Press Enter
3. If prompted, enter the root password.
# Usage
Now you can run "gsudo" from anywhere, even Alt+F2 console. Example:
```
gsudo gedit
```
# Portable
"gsudo" file is a portable version, just modify the permissions and run it:
```
chmod +x gsudo
./gsudo gedit
```
