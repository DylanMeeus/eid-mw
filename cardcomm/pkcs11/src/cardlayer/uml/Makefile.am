if PLANTUML
%.png: %.puml
	@PLANTUML@ -o $(abs_builddir) $<

%.svg: %.puml
	@PLANTUML@ -o $(abs_builddir) -tsvg $<

dist_noinst_DATA = cal.png
endif
EXTRA_DIST = cal.puml
