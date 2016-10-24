
svglist := $(wildcard *.svg)

pdflist := $(svglist)

$(pdfl):

pdfl:

	echo $(pdflist)
#	$(foreach tar,	$(subst svg,pdf,$(pdflist)),make $(tar))
	make $(subst svg,pdf,$(pdflist))

%.pdf : %.svg
	inkscape -f $^ -A ../$@ 