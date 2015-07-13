------------------------------
Langrisser II PC Tools Archive
------------------------------
The purpose of this archive is simple. I finished, for the most part, the
hacking for Langrisser II PC. However, I don't have time to work on the
scripts.

The scripts of this game are based on Langrisser: Dramatic Edition, in
which Masaya completely overhauled the existing Der Langrisser script. This
overhaul included numerous grammar fixes to existing text, and rewriting of
almost everything for clarity, as well as the addition of dozens of lines for
every scenario.

The changes to the existing script made it pointless to write a tool to match
lines from the Der Langrisser script to inject into this game, as it would be,
at best, maybe 15 lines per scenario -- which is nothing when scenarios have
over 200 lines.

This archive is provided so the fans can get the game done on their own.
Whoever organizes the project is fine with me. That's your business and I
don't have time to do it myself. My luck with translation assistance has been
equally limited, so maybe you'll do better than I have.

This just seems the best option to me, rather than listen to people whine
about how long I'm taking with it, when I'm in the same place a year from now
that I am today.

------------------------------
What's Included?
------------------------------
Included are translated versions of all the graphics in the game. You can
just copy them to your install folder and that part of the job is done. The new
title screen was designed by Rosenred, so make sure she gets credit for her
work.

Also included are the Japanese scripts, made from the Langrisser: Dramatic
Edition dumps using CWX's tools, and a few scripts I have already translated
to English, or converted from Der Langrisser (likely the later, but it was
done 6 months ago so I no longer remember). There's also a LANG.FON included.
This is the PC font used for Langrisser I and included the needed menu options
and two fixed-width fonts designed to display with correct spacing in the game.

Another later addition is an IPS patch for the EXE by NightWolve to fix the
game so it no longer crashes at the end of Scenario 1. This problem showed up
on Windows 98, Me, 2000, and XP in Korean mode, so none of us can figure out
how the game ran in the first place...

------------------------------
How to Use
------------------------------
First off, download and install PHP from www.php.net. It's 1MB so don't bitch.
It's a smaller download than Java.

Next, make sure it is in your PATH variable. With 9X, this means editing your
AUTOEXEC.BAT and adding ";C:\PHP" to the existing PATH= line, then rebooting.

With 2000/XP, right click My Computer and pick Properties. Select the Advanced
tab, click on the Environment Variables button, and look in the bottom field
of the new window that pops up. One line is "PATH." Add the same stuff to this
line that you would for AUTOEXEC.BAT.

You're all set.

As you complete script translations, copy the file to the \english\ folder and
rename it from .TXT to .DAT. To test your work, run MAKE.BAT. This will make a
new TDAT.RES to be copied to your translation folder. Now just run the game
and witness your new text.

That's all that's required for insertion.

I don't know what will happen if you try to play a scenario you have not
inserted some file for, so all i can say is rename the Japanese ones and play
with garble and text spills, or just don't do it :)

------------------------------
What's Left?
------------------------------
The character and class names at the bottom of the screen. This requires some
work on the EXE to finish up, and I have a bit of preliminary stuff done, but
not enough to provide with these tools.

In the event you ever finish one full path of the game and you still need these
done, come see me and I'll help you out with it. It's just not worth my effort
to include with these tools at the moment, unless anyone picks them up and
moves the project forward like Moon Knight and Picorat did with Alamone's
tools.

------------------------------
Credits
------------------------------
Please make sure the following people do get credit for their work if you make
a release based off these tools. Please also state that you did use this set
of tools.

         D - Programming
             Scenario 1
             Intro
             Prologues
             System text translations
  Rosenred - Title screen
Nightwolve - Hack to make it playable

---
(c) D 2003,2004
d (at) the2d.com
http://d.the2d.com/
