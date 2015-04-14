# Count words.
#%.dat : books/%.txt wordcount.py
#	@echo

%.dat : books/%.txt wordcount.py
	python wordcount.py $< $@

.PHONY : dats
dats : isles.dat abyss.dat last.dat

analysis.tar.gz : *.dat wordcount.py
	tar -czf $@ $^



