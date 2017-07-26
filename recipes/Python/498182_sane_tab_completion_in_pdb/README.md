## sane tab completion in pdb

Originally published: 2006-10-07 16:22:00
Last updated: 2009-07-06 04:35:33
Author: Stephen Emslie

I make frequent use of python's built-in debugger, but one obvious feature seems to be missing - the bash-like tab completion that you can add to the interpreter. Fortunately pdb's interactive prompt is an instance of Cmd, so we can write our own completion function.