Quick explanatory directory:

The "density" notebook is where I'd start, contains basically how I write dust_density.inp.

"SED Creation" is where I'd go next, shows how I create SEDs. But this should be familiar to you.

"INP Generation" is just there to show how I make some of the other inp files, but this should also probably be familiar. 

And the rest are various inp files used by RADMC. Some I like to create via notebook, others I tweak manually, but the process is largely the same in all cases.

I made this over the course of a few hours, and there is almost certainly parts of the code that are completely self-explanatory to me, but not to you, so feel free to ask any question needed.

FINAL NOTE OF IMPORTANCE: This stuff obviously does nothing if RADMC is not in your system as well. I have it set up so that all of this is in a folder, with the folder being on the same level as the radmc3d-2.0 folder, and that has not given me any trouble. The placement should only matter to anything that uses os.system to run RADMC commands, as that's where I've appended the path, so you may need to alter that.
