dot-files
=========

After you are done cloning this repo you can do one of two things:

1. git submodule update --init --recursive
2. git submodule foreach --recursive git checkout master

The first one will update them from the branch they last worked at.
The second will update all of the things to the most recent branch.

Then run ./mastersync and it will push all the configurations to your home.

Have fun!
