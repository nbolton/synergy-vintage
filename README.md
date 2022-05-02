# Synergy Vintage 🍷

For vintage computer enthusiasts, Synergy Vintage aims to keep the origins of 
[Synergy](https://github.com/symless/synergy-core) alive. You can use Synergy 
Vintage on operating systems available from 2001 to 2005; Windows (95, 98, ME, 
or 2000), Mac OS X (Jaguar to Tiger), and Linux (e.g. Red Hat 7).

![Animated gif of Synergy in 2001](https://raw.githubusercontent.com/nbolton/synergy-vintage/main/doc/images/warp.gif)

> With Synergy, all the computers on your desktop form a single virtual screen. 
> You use the mouse and keyboard of only one of the computers while you use all 
> of the monitors on all of the computers. You tell Synergy how many screens you 
> have and their positions relative to one another. Synergy then detects when the 
> mouse moves off the edge of a screen and jumps it instantly to the neighboring 
> screen. The keyboard works normally on each screen; input goes to whichever 
> screen has the cursor. 
> [Read more](https://github.com/nbolton/synergy-vintage/wiki/About).

## Downloads

- [Windows](https://github.com/nbolton/synergy-vintage/releases/download/1.3.1/Synergy-v1.3.1-release-Windows-9x.zip)
- [Mac OS X](https://github.com/nbolton/synergy-vintage/releases/download/1.1.10/Synergy-v1.1.10-debug-MacOS-10.3.zip)
- Linux (coming soon)

The Mac OS X version is 1.1.10, and the Windows version is 1.3.1.
These two versions are compatible (they work with eachother fine).

The build machine for Windows is Windows 98, but will probably work on 
Windows 95, Windows ME, and possibly Windows 2000.
For the Mac OS X download, the build machine is Mac OS X Panther 10.3,
and the binary may work on similar versions (e.g. 10.2 and 10.4).

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
