# James Philip Rowell

I have over 35 years of experience with computer animation, visual-effects production and software development.
I've worked at a wide range of VFX-studios, from Pacific Data Images/Dreamworks, to Industrial Light & Magic,
Charlex, Reel FX, The Mill, Framestore, Groove Jones, Harbor Picture Company and others.

These days we have amazing GUIs for almost all of our CG-tasks including powerful pipeline tools to
hang all the different programs and data together.
The work we generate ultimately comes down to data in (usually) many thousands of files within some kind of standardized directory-structure on a file server.

Relying on my old-school way of working I ***still*** find it immensely helpful be able to open a
shell in a terminal program to examine the files that way, and as such I've found a few tools to be indispensable. I've written several
myself that were usually standard-issue at the big studios back-in-the-day, but not being publicly available
I took it upon myself to create them.

Note that a UNIX-like environment is the platform of choice at 99.9 % of studios.
So my tools are all written to be used in such an environment, and importantly, by following the Unix philosophy of doing one thing well
and simple enough such that its output can
be piped into other programs for further processing.

My github repos provide these (among other) useful tools.

- `lsseq` - A powerful utility akin to `/bin/ls` but adding the ability to list image-sequences in a compact way.
- `renumseq` - A command-line tool to renumber and/or rename frame sequences, partner to `lsseq`.
- `runsed` - A VERY helpful wrapper for `sed` that let's you easily review and if need be back out changes en-mass.
- `time-stamp` - A command-line tool for printing the date and time which is a suitable embedding in file-names or directory-names.
- `expandseq`/`condenseseq` - two complimentary tools for printing out lists of integers using a simple but standard VFX syntax for listing frame ranges.
- `seqLister` - the python library used by several of those tools above which supports the syntax widely used within the VFX-industry for specifying frame-ranges.

Please checkout my ❤️ [sponsor](https://github.com/sponsors/jrowellfx) ❤️ page for a bit of my history
and to please consider sponsoring my work on github - MUCH APPRECIATED!

Many thanks,  
James.
