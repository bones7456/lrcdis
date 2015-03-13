# lrcdis
Automatically exported from code.google.com/p/lrcdis

lrcdis is a bash script for automatically downloading lyrics and displaying it.

Now compatable with [mpd](http://www.musicpd.org/), [moc](http://moc.daper.net/), [audacious](http://audacious-media-player.org/), [amarok](http://amarok.kde.org/), [exaile](http://www.exaile.org/), [quodlibet](http://code.google.com/p/quodlibet/), [rhythmbox](http://www.rhythmbox.org/), [mplayer](http://www.mplayerhq.hu/), [JuK](http://developer.kde.org/~wheeler/juk.html), [qmmp](http://qmmp.ylsoftware.com/index_en.php), [muine](http://muine-player.org/), [banshee](http://banshee-project.org/), [xmms2](http://xmms2.xmms.se/).

Now supply these display mode:

* CLI: colorful command line method.
* OSD: using gnome-osd-client, give a on-screen-display.
* notify: using notify-send, give a series of message boxs.
* kdialog: using kdialog, KDE users may prefer this mode.
* fifo: output a fifo file /dev/shm/lrcfifo, which can be used by other programs.
* title: display lyrics on terminal's title, such as gnome-terminal.
* echo: directly output lyrics, without any beautify.
