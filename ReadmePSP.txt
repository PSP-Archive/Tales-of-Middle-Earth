ToME 2.3.1 for PSP 0.1:
  by Gendal and abszero
Update to 2.3.5 by Daddy32
  
 ---Quick Description---
	
	Tales of Middle Earth (ToME) is a fantasy adventure game, based on the works of 
J.R.R. Tolkien. It is a game that emphasizes intricate, challenging, and varied gameplay 
over graphics. Hundreds of different monsters in randomly-generated, unpredictable dungeons 
will strive to slay you by various means, and you counter - if you survive - by developing 
the skills of your choice and wielding mighty artifacts. ToME's races from Hobbit to Troll 
and classes from Swordmaster to Summoner allow for many different playing styles and a 
replay value that extends through years.

The only game so realistic that your scrolls and spell books will burn if you trudge in 
lava (unless you have gained immunity from some armour), you will dry up rivers to cast 
mighty spells, strike at orcs with blades attuned to slay them specifically, summon armies 
from a simple totem, and even forge your own artifacts. There is an entire community to 
help you with the game, and it is far from static - ToME is a developing game, always 
improving. And best of all, it's free.

	http://www.t-o-m-e.net/

	
---Setup---
	Copy the 'Tome 2.3.5' folder from the 'GAME' folder
		to the /PSP/GAME directory on your memorystick


---Controls---
	Quick Summary:
		D-Pad:                 Move character (4 way), interface navigation
		Analog Stick:          Move character (8 way)
		Cross:                 Confirm / 'Enter'
		Circle:                Cancel / 'Escape'
		Triangle (held):       Onscreen keyboard (release to select)
		Square (held):         Macro interface
		Square (held) + Cross: Modify macros
		Left Trigger:          CTRL modifier key
		Right Trigger:         Shift modifier key / Run
		Select:                Cycle targets / '*'
		Start:                 Lock on target / 't'
		

	Via Onscreen Keyboard:
		?                      Online help file; 'playing the game' lists commands
		CTRL + x               Save and exit the game


	D-Pad - Move:
		Moves your character up, down, left, or right.  To move diagonally,	which 
		is fairly important in Angband, you would need to use the analog stick 
		described below or the numpad available from the onscreen keyboard (more on
		this later).  On the numpad, directions are as follows:  1 = SW, 2 = S, 
		3 = SE, 4 = W, 6 = E, 7 = NW, 8 = N, and 9 = NE.

	Analog Stick - Alternate Move:
		Moves your character in any of the eight directions.

	Cross - Confirm:
		The confirm button generally.  Maps to the Enter key.  Furthermore, yes/no 
		questions have been modified to treat the cross button as an affirmative 
		response (y and Y are still accepted too).  Many other in-game queries have
		a shortcut response to the Enter key as well.  In stores for example, when 
		you are asked how many of an item you would like, pressing Enter (Cross) 
		will reply with the value '1'.

	Circle - Cancel:
		The cancel button generally.  Maps to the Escape key, thereby cancelling 
		most actions in the game and interface.

	Triangle - Onscreen Keyboard: 
		Brings up the onscreen keyboard (OSK).  As long as you hold the Triangle 
		button, the OSK remains on the screen.  During this time you can move the 
		cursor with the d-pad to select the letter you want.  When you have made 
		your selection, releasing the Triangle button will submit the currently 
		highlighted key to the game.  The OSK remembers the position of the cursor,
		so if you are trying to pick a lock say, you can hold	Triangle, navigate to
		the 'o' key once, release Triangle, and then repeatedly press	Triangle 
		(submitting multiple 'o' presses) until the door opens.  If you have the 
		OSK visible and decide you don't want to enter a key, you can cancel the 
		OSK by pressing Circle.

	Square - Macros:
		Brings up the macro interface.  Unlike the OSK,	the macro interface does 
		not show all the available options at once.  When	you first hold Square, 
		five options appear at the bottom of the screen.  Release the Square button
		will invoke the green option at the center.  If you press an arrow key 
		while	still holding Square, you will instead move to a different 'sub-star'
		according to the arrow symbols on the other 4 options.  

		For	example, in the default macro set, if you hold Square, the option with 
		an up arrow will be a yellow 'Rest HP/MP'.  If you press up while still 
		holding Square, a new	star appears with 'Rest HP/MP' in the center and 
		several other new options surrounding it.  You could now release Square and
		it would select 'Rest HP/MP'.  Alternatively, you	could press another 
		direction to select one of the new sub-stars. Currently there are only two 
		levels of stars: the initial one and its four	sub-stars.  This may change 
		in the future.  

		While this may sound somewhat complicated, with a little practise it is a 
		very efficient way to play the game.  In the default set, for example, you
		can shoot a magic missile at the nearest target just by pressing and 
		releasing Square.  If you want to aim at a different target, hold Square, 
		press Right, then release Square. The star interface puts many options at 
		your fingertips with just a few keypresses.

		What's more, you can modify the set of macros by holding Square to bring
		up the interface and then pressing Cross.  Once you press Cross, you don't 
		need to hold it or Square.  Follow the onscreen directions to make your 
		own macro or press Circle to cancel.  When your macro is finished, it will
		be saved to a file on your memorystick for future use.  When choosing your
		macros, it's a good idea to make the ones you use most often have the
		shortest key sequences.  Also, you might want to organize your macros into
		substars that contain similar macros.  Like in the default set, the 
		up-arrow sub-star is for recovery, left is for detection, down is for
		various dungeon crawling stuff,	and right is for attack magic.

	Left Trigger - CTRL:
		Maps to the CTRL modifier key on a keyboard.  Hold this key down when you
		enter a key via the OSK to enter CTRL + that key instead.  For example, to 
		save and exit (CTRL + X), you would hold Triangle, navigate to 'X', hold 
		the Left Trigger, and release Triangle.  Should be a full CTRL 
		implementation now.

	Right Trigger - Shift:
		Maps to the Shift modifier key on a keyboard.  In the OSK, holding the 
		Right Trigger allows the use of capital letters, etc.  Also, pressing 
		Right Trigger while moving around the Angband map engages 'run' mode. 
		Running is implemented in other versions of Angband by a default macro 
		(part of Angband itself, not the macros accessible through Square) on the 
		Shift + numpad keys.  For this PSP version though, it directly invokes the 
		run command, '.'.  If one were to map a different (Angband core) macro to 
		those keys, the game would ignore the change and continue to run on Right 
		Trigger + direction.

	Select - Cycle targets
		Maps to the asterisk key. Press repeatedly to cycle through nearby targets.

	Start - Lock on target
		Maps to the 't' key. After using Select to choose a target, press Start 
		and you will lock on to that target.  Then in the future, when you fire an 
		arrow	or cast a spell, you can target that enemy by again pressing Start



---Known Issues---
	None, though that doesn't mean there aren't any.

---Bug reports--
	You can either email me at gendal@jrh.net or post in the thread over at 
	http://www.dcemu.co.uk/vbulletin/forumdisplay.php?f=48
	

---Acknowledgements---
	Mostly Abszero for porting Angband to the PSP in the first place, and also 
	the PSPSDK guys for doing all the underlying work that made it so easy. 
	

---History---
	01/10/2010
		- Updated to Tome 2.3.5 (Daddy32)
	v0.1 (07/24/2005)
		-Initial release and differences from the .4 release of Angband:
		-Left Trigger should now act as a full CTRL key, including keys outside of
			the a-z and A-Z ranges.
		-Removed main function from spawning in a seperate thread, greatly increasing 
			speed for any ascii animations like the introduction. Running is now 
			close to instantaneous along with other small improvements.
		-Macro interface reverted back to star shape 
		-Small visual improvements to OSK and Macro interface, including 
			changing key highlight in the OSK to red for easier visibility
		-Added previous message to bottom line next to the Battery display
			since it was going unused and I often missed the last message
			because of macros and whatnot clearing the buffer. 
		-ToME now flushes the input buffer before sending a macro with the star 
			interface, you should not have to use \e\e\e anymore. If anybody can 
			think of a reason this is a bad default, let me know. 

---Compilation Notes---
	Updated PSPSDK to a version off svn on 7/20/2005, otherwise Abszero's notes 
	on angband still apply for ToME:
	
	To compile Angband for PSP, I used the toolchain and PSPSDK from ps2dev.org.
		I used a version pulled from the official svn repository early on 
		07/11/2005.  The PSPSDK is under constant revision, and because I do not 
		use the build.mak file they provide, Angband for PSP may not compile on 
		later versions unmodified.  If you run into trouble compiling your own 
		version, check that the LIBS in Makefile.psp include all the libs that 
		build.mak includes, as this is the most likely source of problems.  

	The build environment was Cygwin 1.5.18-1 running under Windows XP SP2

	In anticipation of submitting this port back to thangorodrim.net, the 
		Makefile is named Makefile.psp.

	Currently Makefile.psp does not compile the 'tolua' program that generates
		the l-xxxxxx.c files.  These c files are included with the other source 
		files however, and were included in the original Angband 3.0.6 source 
		tarball downloaded from http://www.thangorodrim.net .  If you find a need
		to rebuild them, I believe you can use a Makefile for a different system 
		(say Makefile.lsl for linux) and it should generate those files.  

	

---Legal---
PSP port:
	ToME was ported to the PSP by Jack Hyde <gendal@jrh.net>, with most of the 
	initial work being done by Mark Dykstra <mdykstra21@hotmail.com> on Angband.
	You may	do as you like with the source code, subject to the licensing restrictions 
	below.  By putting this program on a PSP or running it, you accept all 
	consequences including the loss of files on your PSP and computer, 'bricking'
	of your PSP, or worse.


PSPSDK:
This program uses the pspsdk which has the following copyright
restrictions

Copyright (c) 2005  adresd
Copyright (c) 2005  Marcus R. Brown
Copyright (c) 2005  James Forshaw
Copyright (c) 2005  John Kelley
All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions
are met:
1. Redistributions of source code must retain the above copyright
   notice, this list of conditions and the following disclaimer.
2. Redistributions in binary form must reproduce the above copyright
   notice, this list of conditions and the following disclaimer in the
   documentation and/or other materials provided with the distribution.
3. The names of the authors may not be used to endorse or promote products
   derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE AUTHORS ``AS IS'' AND ANY EXPRESS OR
IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES
OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED.
IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR ANY DIRECT, INDIRECT,
INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT
NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE,
DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY
THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
(INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF
THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.


Original Angband source:
This program is based on the Angband source code, which is

Copyright (c) 1997 Ben Harrison, James E. Wilson, Robert A. Koeneke

This software may be copied and distributed for educational, research,
and not for profit purposes provided that this copyright and statement
are included in all such copies.  Other copyrights may also apply.


All changes made by Ben Harrison, Robert Ruehlmann, and many other Angband
developers are also available under the GNU GENERAL PUBLIC LICENSE.
Note that this doesn't influence the current distribution, since parts of
the source are still only available under the old Moria/Angband license.
Until all parts of Angband are distributed under the GPL the only valid
license remains the original Moria/Angband license.

More informations about Angband and the GPL can be found at:
http://www.thangorodrim.net/development/opensource.html


