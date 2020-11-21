# $Revision: 1.1 $
#
# This requires GNU make.

# Run twice for cross references.
%.pdf: %.tex
	xelatex $< $@
	makeindex $< $@
	xelatex $< $@


all: horen-lenavi.pdf

horen-lenavi.pdf: $(wildcard *.tex)
