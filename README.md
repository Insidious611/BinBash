# BinBash

BinBash is an IRC quote bot specializing in seperate textual quote files 
for different purposes. In its original incarnation on *irc.slashnet.org*
channel *#mzx*, it replaced !<nick>bash scripts that were used to chronicle funny 
quotes from mostly former community members.

## Usage:

Edit the binbash.py script, putting in the server, nickname, channel, 
etc that your bot will use. Place text files containing quotes in the 
bashes folder, see the examples in that folder. Run the bot with python 
binbash.py. The script will automatically split messages at 440 
characters. If your network has a shorter maximum line length, you may 
want to search-and-replace instances of "440" with whatever line length 
you need.

Enjoy.

## Commands:

!bashes - Shows a listing of files in the bashes/ folder
!foobash n - n is a line number. If n is specified, show the nth line from foo.txt, if it is not specified, show a random line from foo.txt
!addquote foo This is a quote - Add the line "This is a quote" to the end of foo.txt, creating foo.txt if necessary.


If you like this, check out http://github.com/Insidious611/BinBashCord,
a version of this script rewritten seven years later for Discord.
