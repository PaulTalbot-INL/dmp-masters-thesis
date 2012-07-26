#==================================================================#
#  Brenton S. Ching
#  Graduate Research Assistant
#  Oregon State University
#==================================================================#

#==================================================================#
#  This makefile cleans up the LaTex files
#==================================================================#

thesis : 
	latex main.tex
	dvipdf main.dvi  thesis.pdf

clean :
	rm -f *.aux *.log *.dvi *.toc *.lof *.lot
	rm -f ./Sections/*.aux 
	rm -f ./Sections/*.log
	rm -f *~
	rm -f *.backup
	rm thesis.pdf
