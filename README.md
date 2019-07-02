# sandpkg
Welcome to the repository for spkg alpha.(Sandboxed Packaged Manager)!
(This is a branch for versions being tested.)

spkg is now up version 0.03a for OpenTerm!

## Why spkg?
I wanted to try to integrate pip into Libterm by running the default install script,
but it does not work by itself. So, I started this repo to host packages that I modified to work in Libterm.
The main inspiration of spkg was [StaSh](https://github.com/ywangd/stash).

## What's the point of spkg?
I know that Libterm already has something like this, but before you accuse me of reinventing the wheel let me explain.
OpenTerm did not have a package manager, so I created one.
But for Libterm, there was no external repo support for its inbuilt package manager.
Thus, I created spkg to make it easier to test and pull software.
(By the way, spkg uses [this](https://github.com/sn3ksoftware/sandboxrepo) repository by default.)

# - Installation -

spkg is finally ready for OpenTerm! You can download the alpha release by following the instructions below.

## OpenTerm
Run this commands in your shell.

```
curl -O https://raw.githubusercontent.com/sn3ksoftware/sandpkg/testing/openterm/sandinstall.tar.gz
tar -C ~/.scripts -zxvf sandinstall.tar.gz
sandinstall
```
(The installer is a bit buggy right now, so try running sandinstall at least 3 times if it does not work the first time.)
## Libterm(WIP)
Run this command:

```
curl -O https://raw.githubusercontent.com/sn3ksoftware/sandpkg/testing/libterm/install.sh && sh install.sh
```

# - FAQ -
Q: I thot that Libterm has a package manager already?

A: Read the point under 'What's the point of spkg?’

Q: Who is spkg for?

A: CLI masters and programmers who have at least basic command-line skills.
Also, script coders who want a easier way to distribute their code.

Q: Can you please hurry up on the Libterm version? I mean, OpenTerm does not exist on the App Store anymore, etc.

A: I can't really do that because I have more experience working with the Cub coding language right now. As for the Python-based implementation of Libterm, it is a lot easier to port programs over from Pythonista [for example](https://github.com/jsbain/GitHubGet), which can run without modifications, 
but my knowledge of Python is less so than that of Cub, unfortunately. Which means that someday there will be spkg for LibTerm :)
