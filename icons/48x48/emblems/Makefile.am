size = 48x48
context = emblems
iconsdir = $(themedir)/$(size)/$(context)
icons_DATA = 				 		\
		emblem-favorite.png 		\
		emblem-important.png 		\
		emblem-noread.png 		\
		emblem-nowrite.png 		\
		emblem-symbolic-link.png 		\
		emblem-system.png 		\
		printer-error.png 		\
		printer-paused.png 		\
		printer-status-unknown.png
EXTRA_DIST = $(icons_DATA)

install-data-local: install-iconsDATA
	(cd $(DESTDIR)$(themedir)/$(size) && $(ICONMAP) -c $(context) -e $(iconsrcdir)/icons/my-mapping.xml)

uninstall-local:
	rm -Rf $(DESTDIR)$(themedir)/$(size)/$(context)
