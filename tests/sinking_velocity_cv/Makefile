input: clean
	gmsh -3 -bin -algo front3d -bin src/column.geo -o column.msh

clean:
	rm -f  fluidity* *.msh *.ele *.edge *.node *.poly *.vtu *.s *.d.1 *.stat \
	matrixdump matrixdump.info
