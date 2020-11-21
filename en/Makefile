# $Revision: 1.1 $
#
# This requires GNU make.

all: horen-lenavi

horen-lenavi:
	xelatex horen-lenavi
	makeindex horen-lenavi
	xelatex horen-lenavi

clean:
	rm *.ind
	rm *.ilg
	rm *.aux
	rm *.out
	rm *.idx
	rm *.toc
	rm *.log
	rm *.pdf
