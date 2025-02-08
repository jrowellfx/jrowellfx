# James Philip Rowell

I have over 35 years of experience with computer animation, visual-effects production and software development.
I've worked at a wide range of vfx-studios, from Pacific Data Images/Dreamworks, to Industrial Light & Magic,
Charlex, Reel FX, The Mill, Framestore, Groove Jones, Harbor Picture Company and others.

Across all these years there are a few tools that I have found to be indispensable in such an environment. I've provided
them here - Command-line tools that help me and others with our day to day needs.

In the early days, the command-line and programming scripts were all we had,
even digital compositing and character rigging was done via scripts.

Now of course, we have amazing GUIs for all our CG-tasks as well as powerful pipeline tools to
hang all the different programs together.
But ultimately it all comes down to files on a file server, directories, and computer programs processing data.

Even with all these powerful GUIs, I still find it to be immensely helpful be able to open a
shell in a terminal program and get at the files that way.

Throughout all these years a UNIX-like environment has been the platform of choice at 99.9 % of the studios.
From the early days on Silicon Graphics machines, or Sun Workstations, to 
latter days on Linux builds and even MacOS which is Unix based.

So my tools are all written following the Unix philosophy of doing one thing well and expect its output to
be piped into other programs.

My github repos provide these (among other) useful tools.

- `lsseq` - A powerful utility akin to `/bin/ls` but adding the ability to list image-sequences in a compact way.
- `renumseq` - A command-line tool to renumber and/or rename frame sequences, partner to `lsseq`.
- `runsed` - A VERY helpful wrapper for `sed` that let's you easily review and if need be back out changes en-mass.
- `time-stamp` - A command-line tool for printing the date and time which is a suitable embedding in filenames or directory.
- `expandseq`/`condenseseq` - two complimentary tools for printing out lists of integers using a simple but standard VFX syntax for listing frame ranges.
- `seqLister` - the python library used by several of those tools above which supports the syntax widely used within the VFX-industry for specifying frame-ranges.

Please checkout my ❤️ [sponsor](https://github.com/sponsors/jrowellfx) ❤️ page for a bit of my history
and to please consider sponsoring my work on github - MUCH APPRECIATED!

Many thanks,  
James.
