# $Revision: 1.1 $
#
# This requires GNU make.

# Run twice for cross references.
%.pdf: %.tex
	xelatex $< $@
	makeindex $< $@
	xelatex $< $@


all: horen-lenavi.pdf copy

horen-lenavi.pdf: $(wildcard *.tex)

copy:
	cp horen-lenavi.pdf ~/Desktop/WSA\ Sync/.
