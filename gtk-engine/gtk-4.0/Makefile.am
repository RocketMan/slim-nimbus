SUBDIRS = assets

themedir = $(datadir)/themes/$(PACKAGE)/gtk-4.0
darkthemedir = $(datadir)/themes/$(PACKAGE)-dark/gtk-4.0
lightthemedir = $(datadir)/themes/$(PACKAGE)-light/gtk-4.0
theme_DATA =	gtk.css \
		gtk-dark.css \
		gtk-light.css \
		settings.ini \
		thumbnail.png

EXTRA_DIST = $(theme_DATA)

install-data-local:
	$(mkinstalldirs) $(DESTDIR)$(darkthemedir);
	for i in $(theme_DATA); do   \
	  (cd $(DESTDIR)$(darkthemedir) && ln -fs ../../$(PACKAGE)/gtk-4.0/$$i .)  \
	done
	(cd $(DESTDIR)$(darkthemedir) && rm -f gtk.css && ln -fs gtk-dark.css gtk.css);
	$(mkinstalldirs) $(DESTDIR)$(lightthemedir);
	for i in $(theme_DATA); do   \
	  (cd $(DESTDIR)$(lightthemedir) && ln -fs ../../$(PACKAGE)/gtk-4.0/$$i .)  \
	done
	(cd $(DESTDIR)$(lightthemedir) && rm -f gtk.css && ln -fs gtk-light.css gtk.css);

