#WTFTW wiki

this is a little wiki of tips for [WTFTW (Window Tiling For The Win - the tiling window manager)](https://github.com/Kintaro/wtftw)

[Click here to make edits to this page](https://github.com/nathanross/wtftw-wiki/edit/master/README.md) (It is easy to create a github acocunt if you do not have one.)


## Getting Started

#### Help, it's not working!

 * I started WTFTW but I don't see anything, it is a black screen and nothing happens.

Do not worry! by default WTFTW

 * Does not open any programs! If you see a black screen, try Alt+Shift+Enter to open a "shell" (a 'command line'). If it is not working for you, try toggling caps lock.

 * must compile new or changed config files before any program can be opened. This can take a few seconds on entry-level PCs but will definitely be faster in a few months (Reason: the rust language's compiler is not being very compilation optimized yet, this still takes a few seconds, but rust is currently undergoing heavy compilation optimization, so in the future this will be faster.)

#### A "shell"? How do I use my computer from this?

 * if you are unfamiliar with shells, don't worry, you can still use your computer before you've learned to make great use of it. once a shell opens, type an exclamation mark, a space, then the name of your favorite installed program like ```! chromium``` or ```! localc``` then press enter. Now you are cooking ! You no longer need to navigate through start menu directories.

* The terminal is very powerful and in time, you can learn to do faster and better with it many functions that you used other programs for (file exploration and searching, system utilities). E.g. on ubuntu just type ```apt-get install libreoffice-calc``` to install Libreoffice Calc.

## Customizing it

### How do I see my WTFTW configuration changes while I edit it?

Just like there is a shortcut key for "open terminal" (```alt+shift+enter```),there is a shortcut key for reloading the configuration. (```alt+q```) 

WTFTW reload of configuration ("restart WTFTW") happens without disrupting existing programs; it takes a couple seconds (if you changed the configuration) and while it is running you cannot interact with WTFTW (example, you cannot change the focused window or use shortcut keys). You can tell it has finished loading because of the changes taking place and being able to use shortcut keys again.

The shortcut key to reload configuration, like all shortcut keys, can be edited through your configuration file. Note that in wtftw, the pertinent action is called "restart"

