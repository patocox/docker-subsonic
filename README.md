# Subsonic Docker Image on Busybox
Small footprint image - ~190MB for running [Subsonic](http://www.subsonic.org/).

Sample docker run:

`docker run -d -p 4040:4040 patocox/subsonic-busybox`

Optionally, volume mount your music directory to /var/music.

`docker run -d -p 4040:4040 -v /music_directory:/var/music patocox/subsonic-busybox`

Browse to 4040 to view the GUI.
