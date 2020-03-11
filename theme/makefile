all: 
	# build the SVG-based icons
	make buttons.gif tab-sel-menu.gif tab-unsel-menu.gif 
	# build the miscellaneous PNG-based icons
	make lock.gif newwindow.gif resize.gif 
	# build the tab-selection PNG-based icons
	make tab-sel-left.gif tab-sel-mid.gif tab-sel-right.gif tab-unsel-left.gif tab-unsel-mid.gif tab-unsel-right.gif

buttons.gif: buttons.svg
	inkscape -f buttons.svg -e buttons.png
	convert buttons.png buttons.gif
	# clean up the intermediate file
	rm buttons.png

tab-sel-menu.gif: tab-sel-menu.svg
	inkscape -f tab-sel-menu.svg -e tab-sel-menu.png
	convert tab-sel-menu.png tab-sel-menu.gif
	# clean up the intermediate file
	rm tab-sel-menu.png

tab-unsel-menu.gif: tab-unsel-menu.svg
	inkscape -f tab-unsel-menu.svg -e tab-unsel-menu.png
	convert tab-unsel-menu.png tab-unsel-menu.gif
	# clean up the intermediate file
	rm tab-unsel-menu.png

lock.gif: lock.png
	convert lock.png lock.gif

newwindow.gif: newwindow.png
	convert newwindow.png newwindow.gif

resize.gif: resize.png
	convert resize.png resize.gif

tab-sel-left.gif: tab-sel-left.png
	convert tab-sel-left.png tab-sel-left.gif

tab-sel-mid.gif: tab-sel-mid.png
	convert tab-sel-mid.png tab-sel-mid.gif

tab-sel-right.gif: tab-sel-right.png
	convert tab-sel-right.png tab-sel-right.gif

tab-unsel-left.gif: tab-unsel-left.png
	convert tab-unsel-left.png tab-unsel-left.gif

tab-unsel-mid.gif: tab-unsel-mid.png
	convert tab-unsel-mid.png tab-unsel-mid.gif

tab-unsel-right.gif: tab-unsel-right.png
	convert tab-unsel-right.png tab-unsel-right.gif

.PHONY: clean

clean: 
	#rm buttons.png tab-sel-menu.png tab-unsel-menu.png 
	#rm buttons.gif tab-sel-menu.gif tab-unsel-menu.gif 
	#rm lock.gif newwindow.gif resize.gif tab-sel-left.gif tab-sel-mid.gif tab-sel-right.gif tab-unsel-left.gif tab-unsel-mid.gif tab-unsel-right.gif
	rm *.gif
