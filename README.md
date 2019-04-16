# sandpkg
Welcome to the repository for sandpkg (Sandboxed Packaged Manager)!

## Why spkg?
I wanted to try to integrate pip into Libterm by running the default install script,
but it does not work by itself. So, I started this repo to host packages that I modified to work in Libterm.
The main inspiration of spm was [StaSh](https://github.com/ywangd/stash).

## What's the point of spkg?
I know that Libterm already has something like this, but before you accuse me of reinventing the wheel let me explain.
OpenTerm did not have a package manager, so I created one.
But for Libterm, there was no external repo support for its inbuilt package manager.
Thus, I created spkg to make it easier to test and pull software.
(By the way, spkg uses [this](https://github.com/sn3ksoftware/sandboxrepo) repository by default.)

# - Installation (WIP, not ready yet) -

spkg is not ready yet for Libterm, but an alpha release of spkg for OpenTerm will be avaliable soon (once I get the install and remove systems working and all the confusing github repo stuff.)

## OpenTerm
Run this command in your shell.

```
curl -O https://raw.githubusercontent.com/sn3ksoftware/sandpkg/master/openterm/install.cub && cub install.cub
```

## Libterm
Run this command:

```
curl -O https://raw.githubusercontent.com/sn3ksoftware/sandboxrepo/master/openterm/install.sh && sh install.sh
```

# - FAQ -
Q: I thot that Libterm has a package manager already?

A: Read the point under 'What's the point of spkg?'

Q: Who is spkg for?

A: CLI masters and programmers who have at least basic command-line skills.
