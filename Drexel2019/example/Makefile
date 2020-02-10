TEX_NAME = presentation

all:
	pdflatex ${TEX_NAME}.tex
	pdflatex ${TEX_NAME}.tex
	# bibtex each citation class separately
#	bibtex ${TEX_NAME}
#	pdflatex ${TEX_NAME}.tex
	pdflatex ${TEX_NAME}.tex
	#Make a ps suitable for PDF generation
#	dvips -t letter -Ppdf ${TEX_NAME}.dvi -o ${TEX_NAME}.ps
#	ps2pdf ${TEX_NAME}.ps ${TEX_NAME}.pdf
#	#Replace PS with a regular one
#	dvips -Ppdf -t letter -G0 ${TEX_NAME}.dvi -o ${TEX_NAME}.ps
clean:
	rm -f *.dvi *.log *.aux *.ind *.ilg *.toc *.end *.bbl *.blg
