## Windows Subsystem for Linux (WSL)

- Run Bash shell scripts and Linux command-line applications 

- Install additional Linux tools using the distribution's built in package manager (apt-get, for example).

- Invoke Linux applications on Windows.

## configuration
[installation in 2 minutes :)](https://blogs.msdn.microsoft.com/commandline/2016/04/06/bash-on-ubuntu-on-windows-download-now-3/)

```
    // the shell to run when spawning a new session (i.e. /usr/local/bin/fish)
    // if left empty, your system's login shell will be used by default
    // make sure to use a full path if the binary name doesn't work
    // (e.g `C:\\Windows\\System32\\bash.exe` instad of just `bash.exe`)
    shell: 'C:\\Windows\\System32\\bash.exe',
    // for setting shell arguments (i.e. for using interactive shellArgs: ['-i'])
    // by default ['--login'] will be used
    shellArgs: ['--login'],
```

## Git Bash

Git Bash is a command-line Git client that comes with Git for Windows

## configuration 
[installation in 2 minutes :)](https://git-for-windows.github.io/)

```
    // the shell to run when spawning a new session (i.e. /usr/local/bin/fish)
    // if left empty, your system's login shell will be used by default
    // make sure to use a full path if the binary name doesn't work
    // (e.g `C:\\Windows\\System32\\bash.exe` instad of just `bash.exe`)
    shell: 'C:\\Program Files\\Git\\git-cmd.exe',

    // for setting shell arguments (i.e. for using interactive shellArgs: ['-i'])
    // by default ['--login'] will be used
    shellArgs: ['--command=usr/bin/bash.exe', '-l', '-i'],
```

## PowerShell

PowerShell is the default Windows command line shell designed especially for system administrators.

- Accepts and returns .NET Framework objects.
- Provides completely new tools and methods for managing and configuring Windows.
- Windows PowerShell providers allow you to access other data stores, such as the registry and digital signature certificate stores, as easily as you access the file system.

## configuration
Comes preinstalled with every version of Windows.

```
    // the shell to run when spawning a new session (i.e. /usr/local/bin/fish)
    // if left empty, your system's login shell will be used by default
    // make sure to use a full path if the binary name doesn't work
    // (e.g `C:\\Windows\\System32\\bash.exe` instad of just `bash.exe`)
    shell: 'C:\\Windows\\System32\\WindowsPowerShell\\v1.0\\powershell.exe',

    // for setting shell arguments (i.e. for using interactive shellArgs: ['-i'])
    // by default ['--login'] will be used
    shellArgs: [],
```

## CMD

The classic Windows command line interface that was the default before Windows 10 Creator's Update.

## configuration
Comes preinstalled with every version of Windows.

```
    // the shell to run when spawning a new session (i.e. /usr/local/bin/fish)
    // if left empty, your system's login shell will be used by default
    // make sure to use a full path if the binary name doesn't work
    // (e.g `C:\\Windows\\System32\\bash.exe` instad of just `bash.exe`)
    shell: 'C:\\Windows\\System32\\cmd.exe',
    //shell: 'C:\\Windows\\System32\\WindowsPowerShell\\v1.0\\powershell.exe',

    // for setting shell arguments (i.e. for using interactive shellArgs: ['-i'])
    // by default ['--login'] will be used
    shellArgs: [],
```

