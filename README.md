# Subsonic Docker Image on Busybox
Small footprint image - ~190MB for running subsonic.

Sample docker run:

`docker run -d -p 8080:4040 patocox/subsonic-busybox`

Optionally, volume mount your music directory to /var/music.

`docker run -d -p 8080:4040 -v /music_directory:/var/music patocox/subsonic-busybox`

Browse to 8080 to view the GUI.
