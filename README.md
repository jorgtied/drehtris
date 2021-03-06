
# Drehtris / Rotatris

An old Tetris variant for MS DOS from 1993 with a rotating field as well as a two-player mode. The original program in Pascal seems to be lost but the binaries still exist and are preserved here. The original version was distributed as shareware with a small fee for updating to the full version. Those were the times. The game can still be played on common DOS emulators like DOSBox (https://www.dosbox.com) with its frontends for various operating systems. I successfully used it on my Mac with the Boxerapp from http://boxerapp.com.


## Quickstart

* get a dos emulator such as DOSBox
* `git clone https://github.com/jorgtied/drehtris.git`
* start `DREHTRIS.BAT` (for German) or `ROTATRIS.BAT` (for English)
* enjoy (and don't laugh about the primitive implementation and the silly name of the game)


## The game

The game works like standard Tetris with the additional twist that the entire field rotates from time to time. In the beginning it does this with a 180 degrees rotation but later there will be 90 degree rotations as well. Make sure that you build your structures to cope with those rotations. Drehtris features different modes that can even be customized with different field size, speed and rotation schedules. I don't remember the exact details. It keeps a "hall of fame" for each setup.

![screenshot](DREHTRIS.png "Drehtris Screenshot")


## The two-player mode

A bit experimental but still working is the two-player mode. There are two of those rotating Tetris fields that are controled by one player each. The goal is to catch the other player by rotating 90 degrees with your own field. Playing fast is the way to do that. But be aware of the 90 degree rotations that make it hard to survive.

There are statistics for individual duels and overall games that have been played in two-player mode. The keys to be used for each player can be adjusted in the "settings".


## License

DREHTRIS (c) 1993 by Joerg Tiedemann

DREHTRIS is licensed under a
Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License.

You should have received a copy of the license along with this
work. If not, see <http://creativecommons.org/licenses/by-nc-sa/4.0/>.

