RuTorrent for Yunohost
============

Install ruTorrent + rtorrent + libtorrent



Info
----

This package install only a shared instance of rutorrent/rtorrent.

(Every user who has access to rutorrent sees all the torrents)

This installer need to compile libtorrent/rutorrent so it can take a while to complete.

Install
-------
With the install option from admin panel
- Find textbox tagged as Install from github
- Copy and paste: https://github.com/yolateng0/rutorrent_ynh

or from command line `sudo yunohost app install https://github.com/yolateng0/rutorrent_ynh`

Upgrade
------
`sudo yunohost app upgrade ruTorrent https://github.com/yolateng0/rutorrent_ynh`

Versions
--------

rtorrent v0.9.6 and libtorrent 1.1.0
https://github.com/rakshasa/rtorrent   http://rtorrent.net/downloads/
https://github.com/arvidn/libtorrent   https://sourceforge.net/projects/libtorrent/files/libtorrent/libtorrent-0.14.7/
# rutorrent_ynh
