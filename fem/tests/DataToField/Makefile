# Temperature limited from above and top
#
run:
	$(ELMER_GRID) 1 2 square
	$(ELMER_SOLVER)

clean:
	/bin/rm test.log temp.log mon.out
	/bin/rm -r square
