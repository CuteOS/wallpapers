cmake_minimum_required(VERSION 3.5)
project(unsplash-wallpapers)

set(BACKGROUNDS
	default.jpg
	fishcde.jpg
	ear.jpg
	edefault.jpg
	hd-wallpaper-2836301_1920.jpg
	wallpaper-1.jpg
	wallpaper-2.jpg
)

install(FILES ${BACKGROUNDS} DESTINATION /usr/share/backgrounds/cuteos)
