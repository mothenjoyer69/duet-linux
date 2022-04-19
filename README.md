# duet-linux
Linux for the Lenovo Duet

Primarily a rework/rewrite of Cadmium with a direct focus on the Duet (kukui-krane). More of a playing/testing ground for now.

As it stands, currently a Gentoo, Alpine, and Debian install all work (Couple of issues). Gentoo and Debian are purely for testing; They are not the actual target in any way.

Build info: ``./install /dev/sdX -buildoption -rootfs -device``

Build options are: build (Builds kernel, or rebuilds) or nobuild
Rootfs options are: Alpine, Gentoo, Debian
Device options are: Nyan, Krane
