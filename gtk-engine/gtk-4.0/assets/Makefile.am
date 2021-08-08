assetsdir = $(datadir)/themes/$(PACKAGE)/gtk-4.0/assets
darkassetsdir = $(datadir)/themes/$(PACKAGE)-dark/gtk-4.0/assets
lightassetsdir = $(datadir)/themes/$(PACKAGE)-light/gtk-4.0/assets
assets_DATA =	checkbox-checked-active.png \
	checkbox-checked-active@2.png \
	checkbox-checked-insensitive-unfocused.png \
	checkbox-checked-insensitive-unfocused@2.png \
	checkbox-checked-insensitive.png \
	checkbox-checked-insensitive@2.png \
	checkbox-checked-over.png \
	checkbox-checked-over@2.png \
	checkbox-checked-unfocused.png \
	checkbox-checked-unfocused@2.png \
	checkbox-checked.png \
	checkbox-checked@2.png \
	checkbox-mixed-active.png \
	checkbox-mixed-active@2.png \
	checkbox-mixed-insensitive-unfocused.png \
	checkbox-mixed-insensitive-unfocused@2.png \
	checkbox-mixed-insensitive.png \
	checkbox-mixed-insensitive@2.png \
	checkbox-mixed-over.png \
	checkbox-mixed-over@2.png \
	checkbox-mixed-unfocused.png \
	checkbox-mixed-unfocused@2.png \
	checkbox-mixed.png \
	checkbox-mixed@2.png \
	checkbox-unchecked-active.png \
	checkbox-unchecked-active@2.png \
	checkbox-unchecked-insensitive-unfocused.png \
	checkbox-unchecked-insensitive-unfocused@2.png \
	checkbox-unchecked-insensitive.png \
	checkbox-unchecked-insensitive@2.png \
	checkbox-unchecked-over.png \
	checkbox-unchecked-over@2.png \
	checkbox-unchecked-unfocused.png \
	checkbox-unchecked-unfocused@2.png \
	checkbox-unchecked.png \
	checkbox-unchecked@2.png \
	close-active.png \
	close-backdrop.png \
	close-hover.png \
	close-normal.png \
	Makefile.am \
	maximize-active.png \
	maximize-backdrop.png \
	maximize-hover.png \
	maximize-normal.png \
	minimize-active.png \
	minimize-backdrop.png \
	minimize-hover.png \
	minimize-normal.png \
	radio-checked-active.png \
	radio-checked-active@2.png \
	radio-checked-insensitive-unfocused.png \
	radio-checked-insensitive-unfocused@2.png \
	radio-checked-insensitive.png \
	radio-checked-insensitive@2.png \
	radio-checked-over.png \
	radio-checked-over@2.png \
	radio-checked-unfocused.png \
	radio-checked-unfocused@2.png \
	radio-checked.png \
	radio-checked@2.png \
	radio-mixed-active.png \
	radio-mixed-active@2.png \
	radio-mixed-insensitive-unfocused.png \
	radio-mixed-insensitive-unfocused@2.png \
	radio-mixed-insensitive.png \
	radio-mixed-insensitive@2.png \
	radio-mixed-over.png \
	radio-mixed-over@2.png \
	radio-mixed-unfocused.png \
	radio-mixed-unfocused@2.png \
	radio-mixed.png \
	radio-mixed@2.png \
	radio-unchecked-active.png \
	radio-unchecked-active@2.png \
	radio-unchecked-insensitive-unfocused.png \
	radio-unchecked-insensitive-unfocused@2.png \
	radio-unchecked-insensitive.png \
	radio-unchecked-insensitive@2.png \
	radio-unchecked-over.png \
	radio-unchecked-over@2.png \
	radio-unchecked-unfocused.png \
	radio-unchecked-unfocused@2.png \
	radio-unchecked.png \
	radio-unchecked@2.png \
	restore-active.png \
	restore-backdrop.png \
	restore-hover.png \
	restore-normal.png \
	scrollbar-slider-h.png \
	scrollbar-slider-v.png \
	stepper-down.png \
	stepper-left.png \
	stepper-right.png \
	stepper-up.png \
	trough-h.png \
	trough-v.png

EXTRA_DIST = $(assets_DATA)

install-data-local:
	$(mkinstalldirs) $(DESTDIR)$(darkassetsdir);
	for i in $(assets_DATA); do   \
	  (cd $(DESTDIR)$(darkassetsdir) && ln -fs ../../../$(PACKAGE)/gtk-4.0/assets/$$i .)  \
	done
	$(mkinstalldirs) $(DESTDIR)$(lightassetsdir);
	for i in $(assets_DATA); do   \
	  (cd $(DESTDIR)$(lightassetsdir) && ln -fs ../../../$(PACKAGE)/gtk-4.0/assets/$$i .)  \
	done
