# This repository is intended to be used as helper to configure texstudio


## Texstudio configuration file
texstudio.ini is the config file of texstudio. It includes all settings and macro definitions. The configuration file must be placed at a specific place:
- Linux: /home/$USER/.config/texstudio

## Texstudio makefile
To use a makefile instead of using the latex compiler some configurations must be done:

### Linux
TODO

### Flatpak
If the flatpak package of texstudio is used the system environment variables are not available. So setting TEXMFHOME in the system is not reachable in the flatpak package.
TODO

### Windows
Prerequirements:

- Texstudio: https://www.texstudio.org/
- Texlive Windows: https://tug.org/texlive/windows.html
- Git: https://git-scm.com/

![Setup Texstudio Makefile Compiler for Windows](SetupTexstudioMakefileCompilerWindows.pdf)
