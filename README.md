# Synergy Vintage 🍷

> [!TIP]
> ### Update, 20 Nov 2024
>
> This is a hobby project of mine that I use for my vintage computer lab (comprised of vintage Windows, macOS, and Linux computers).
> If you're looking for a version that works on the latest operating systems,
> then modern [Synergy](https://symless.com/synergy) or [Deskflow](https://github.com/deskflow/deskflow) will be best.
> 
> My vintage computer lab has been in boxes while I'm reorganizing my garage (which is also full of boxes).
> Once I have my vintage computer lab back up and running, I'll be doing some development on popular 2006 Linux distros,
> Ubuntu 6.06 and Fedora Core 5.
>
> — [@nbolton](https://github.com/nbolton) (maintainer)

For vintage computer enthusiasts, Synergy Vintage aims to keep the origins of 
[Synergy](https://symless.com/synergy) alive. You can use Synergy 
Vintage on operating systems available from 1995 to 2006; Windows (95, 98, ME, 
2000, and XP), Mac OS X (Jaguar to Tiger), and Linux (e.g. Red Hat 7).

![Animated gif of Synergy in 2001](https://raw.githubusercontent.com/nbolton/synergy-vintage/main/doc/images/warp.gif)

Make all your computers feel like a single device. Move between them seamlessly while staying focused on your task.

> With Synergy, all the computers on your desktop form a single virtual screen. 
> You use the mouse and keyboard of only one of the computers while you use all 
> of the monitors on all of the computers. You tell Synergy how many screens you 
> have and their positions relative to one another. Synergy then detects when the 
> mouse moves off the edge of a screen and jumps it instantly to the neighboring 
> screen. The keyboard works normally on each screen; input goes to whichever 
> screen has the cursor. 
> [Read more](https://github.com/nbolton/synergy-vintage/wiki/About).

## Downloads

### v1.3.1 (2nd April 2006)

Backwards compatible with v1.1.10.

- [Windows](https://github.com/nbolton/synergy-vintage/releases/download/1.3.1/Synergy-v1.3.1-release-Windows-98.zip)
- [Mac OS X](https://github.com/nbolton/synergy-vintage/releases/download/1.3.1/Synergy-v1.3.1-release-MacOSX-10.4.zip)
- Linux (coming soon)

The Windows download for 1.3.1 is built on Windows 98, but the download will 
probably work on Windows 95, Windows ME, and possibly Windows 2000.
For the Mac OS X download of 1.3.1, it's built on Mac OS X Tiger 10.4 using the
10.3.9 SDK, so as well as working on Mac OS X 10.4, it will probably work on
any version of Mac OS X 10.3, but is unlikely to work with older versions of 
Mac OS X (such as 10.2 and below).

### v1.1.10 (12th November 2004)

- Windows (coming soon)
- [Mac OS X](https://github.com/nbolton/synergy-vintage/releases/download/1.1.10/Synergy-v1.1.10-debug-MacOS-10.3.zip) (debug version)
- Linux (coming soon)

The Mac OS X download of 1.1.10 is built on Mac OS X Panther 10.3 using the 10.2
deployment target, so it's likely that this will work on both Mac OS X 10.3 and 10.2,
but is unlikely to work on earlier versions of Mac OS X such as 10.1. It's also
a debug version, which is useful for developers.

## History

Work started on Synergy in 2001 by Chris Schoenenman, inspired by an earlier 
version called CosmoSynergy. Synergy's predecessor was an internal
tool at Cosmo Software (an SGI subsidiary) created out of frustration with 
KVM switches.

> The first incarnation of Synergy was CosmoSynergy, created by Richard Lee 
and Adam Feder then at Cosmo Software, Inc., a subsidiary of 
> SGI (nee Silicon Graphics, Inc.), at the end of 1996. They wrote it, and 
> Chris Schoeneman contributed, to solve a problem: most of the engineers in 
> Cosmo Software had both an Irix and a Windows box on their desks and 
> switchboxes were expensive and annoying. CosmoSynergy > was a great success 
> but Cosmo Software declined to productize it and the company was later 
> closed.
> Synergy is a from-scratch reimplementation of CosmoSynergy. It provides most
> of the features of the original and adds a few improvements.

Though, versions as early as 
[v0.9.8](https://web.archive.org/web/20021102070634/http://sourceforge.net/project/showfiles.php?group_id=59275)
were published in November 2002, those binaries and source archives are sadly 
long gone. The earliest version we have on record is 
[v1.0.14](https://github.com/nbolton/synergy-vintage/releases/tag/1.0.14)
from the 24th of August, 2003.

## Post-Vintage

The transition from Synergy Vintage to Synergy Classic is marked by the 
introduction of the Qt GUI circa 2009. The last recorded version of the 
Qt GUI is 
[1.3.5](https://github.com/symless/synergy-core/releases/tag/1.3.5). 
The last recorded version of Synergy without Qt is 
[1.3.1](https://github.com/nbolton/synergy-vintage/releases/tag/1.3.1),
and this is what Synergy Vintage is based on.
