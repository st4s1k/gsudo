# gsudo (GUI sudo)
gksu/gksudo alternative for debian based distros, nothing fancy

# Installation
To be able to access this command from anywhere, run the installer script only.

#### One line command:
Just copy-paste, press Enter and type the root password.
```
git clone git@github.com:st4s1k/gsudo.git && cd gsudo && chmod +x gsudo_installer && bash ./gsudo_installer
```

#### Separate commands:
Execute each command one-by-one.
```
git clone git@github.com:st4s1k/gsudo.git
cd gsudo
chmod +x gsudo_installer
./gsudo_installer
```

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
