# A Port Of Jonesforth To MIPS32 Architecture
## Tentative Name: Paulforth

Once upon a time Richard WM Jones created a [Forth](http://www.forth.org/whatis.html) implementation for the x86 chips.

It became popular for several reasons:

1. It's written in a literate programming style which makes it an excellent tutorial on how to implement Forth, and how Forth works.

2. A whole lot of people have x86 systems.

3. It's completely free (public domain) and there weren't a lot of good choices for free Forth. Note there is now a GNU implementation [GForth](https://www.gnu.org/software/gforth/) which appears to work well.


Richard WM Jones's original implementation and blog entries on Jonesforth can be found here here:
http://rwmj.wordpress.com/2010/08/07/jonesforth-git-repository/

This fork of Jonesforth has two goals:

1. Implement Forth on a MIPS32 architecture. The original target was a [Microchip Technology, Inc.](http://microchip.com) [PIC32](http://www.microchip.com/design-centers/32-bit) chip, which implements the MIPS32 Revision 2 standard.

2. Update Jones' original tutorial text to replace x86-specific references with the equivalent MIPS32 concept.
