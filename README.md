## Bash File Settings And Configurations I Use With Linux 🐧👾

## ScreenShots of Bash Terminal

![screenshot](https://github.com/iNightjar/BashFile/blob/master/screenshots/screenshot1.png)
![screenshot](https://github.com/iNightjar/BashFile/blob/master/screenshots//screenshot2.png)
![screenshot](https://github.com/iNightjar/BashFile/blob/master/screenshots//screenshot3.png)
![screenshot](https://github.com/iNightjar/BashFile/blob/master/screenshots//screenshot4.png)

## Getting started

### Setting the enviroment

you can clone the reposatory using below in your terminal

```bash
cd ~
git clone https://github.com/iNightjar/BashFile.git
```

### Backup your default bash configurations

let's make a backup from the default files in case something goes wrong

```bash
cd ~
mkdir bashFilesBackup
echo ~/bashFilesBackup/ | xargs -n 1 cp -v ~/.bash*
```

### Replace default .bash files

you can replace your default linux .bash files with mine

```bash
cd ~/BashFile/
echo ~/ | xargs -n 1 cp -v /.bash*
```

### Modify absolute inside .bashrc file

modify the absolute pathes used inside the .bashrc file according to your preffered settings

## Bash Theme I Used

Check this repo, I used their themes in my terminal.
![Bash It](https://github.com/Bash-it/bash-it)

You can find all installation and configuration steps in there documentation too.
![Documentation](https://bash-it.readthedocs.io/en/latest/)
