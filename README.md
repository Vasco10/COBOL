# COBOL
According to Simon Sobisch (gnu.org, 2017), GnuCOBOL covers substantially COBOL 85, 2002, 2014 standards and X/Open COBOL and supports many extensions from IBM COBOL, MicroFocus COBOL, ACUCOBOL-GT and others.


# Installing COBOL on Ubuntu 20.04+

Apart from a few keywords, the GNU-COBOL works well with older compilers.

Be aware though, to have the highest compatibility you need to have all the keywords, paragraphs, ... in UPPERCASE.


## COBOL IDE through VS Code
0. Either you install Ubuntu 20.04 LTS or greater on a physical machine or as a virtual machine.

1. Install Visual Studio Code from Ubuntu software.

2. Open the terminal, update the repos and install any software upgrades, your password will be asked:

        sudo apt update && sudo apt upgrade -y

3. Install GNU-COBOL, the current version 3 and NOT version 4 (called also BETA), your password may be asked:

        sudo apt install gnucobol -y



## Install from Extensions on VS Code
1. COBOL Themes (Bitlang)

2. COBOL (Bitlang)

3. COBOL Language Dictionary - Code Spell Checker

4. COBOL Spell Checker  (this extension is dependent on COBOL Language Dictionary - point 3)

5. Restart your machine (it is optional, but always do it, just to be on the safe side).

![reboot](https://user-images.githubusercontent.com/29803730/130208470-196613a1-9329-4cf1-b4a0-b13b41f191aa.png)





