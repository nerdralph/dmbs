DMBS - Dean's Makefile Build System simplified
===================================

This is a fork of DMBS, simplified with defaults for AVR8 development
http://github.com/abcminiuser/dmbs

Project Overview
----------------

DMBS is designed for AVR-8 and AVR-32 development.  This simplified version has
defaults for AVR8 (ATtiny/ATmega) MCUs programmed with a USBasp programmer.


Use:
----------------

[A template user makefile] (http://github.com/nerdralph/dmbs/blob/master/Template/makefile)
is provided in the `Template` directory.  DMBS modules
are included via a GNU Make `include` directive. While the DMBS `core` module is
always required, you can pick and choose what other modules you wish to add to
your user project.

Each DMBS module can optionally supply one or more Make variables and macros,
which you can reference in your user makefile. Additionally, modules can require
one or more variables to be set by the user makefile, with (in some cases) sane
defaults used if left out.

As modules are added, you can get a list of available targets by simply typing
`make help` from the command line. This will produce a formatted list of targets
as well as mandatory and optional variables and exposed variables and macros.


License
----------------

DMBS is released into the public domain, making is suitable for use everywhere,
by everyone. Contributions are greatly appreciated however, in order to make
DMBS better for everyone.

The actual license text is as follows:

	This is free and unencumbered software released into the public domain.

	Anyone is free to copy, modify, publish, use, compile, sell, or
	distribute this software, either in source code form or as a compiled
	binary, for any purpose, commercial or non-commercial, and by any
	means.

	In jurisdictions that recognize copyright laws, the author or authors
	of this software dedicate any and all copyright interest in the
	software to the public domain. We make this dedication for the benefit
	of the public at large and to the detriment of our heirs and
	successors. We intend this dedication to be an overt act of
	relinquishment in perpetuity of all present and future rights to this
	software under copyright law.

	THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
	EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
	MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
	IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR ANY CLAIM, DAMAGES OR
	OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE,
	ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
	OTHER DEALINGS IN THE SOFTWARE.

	For more information, please refer to <http://unlicense.org/>
