# LSwitch #

Use any key to switch input languages, usage: lswitch [keycode] [keycode for disable]. Keycode is optional and defaults to CAPSLOCK.

- Original code by Haali      - http://haali.su/winutils/
- Small changes by Rumpel     - http://rumpel.k66.ru/lswitch.html

# Build #
## MingW ##
- gcc -Wall -O2 -fno-ident -fomit-frame-pointer -fno-exceptions -fno-asynchronous-unwind-tables -flto -s lswitch.c -nostdlib -lkernel32 -luser32 -lshell32 -lmsvcrt -Wl,-exMain -mwindows