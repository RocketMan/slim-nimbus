SUBDIRS = gtk-2.0 gtk-3.0 images 

INCLUDES = $(GTK2_CFLAGS)

enginedir = $(libdir)/gtk-2.0/$(GTK2_VERSION)/engines
engine_LTLIBRARIES = libslimnimbus.la

libslimnimbus_la_SOURCES =              \
        nimbus_rc_style.c   \
        nimbus_rc_style.h   \
        nimbus_style.c              \
        nimbus_style.h              \
        nimbus_utils.h              \
        nimbus_utils.c              \
        nimbus_theme_main.c

libslimnimbus_la_LDFLAGS = -module -avoid-version
libslimnimbus_la_LIBADD =  $(GTK2_LIBS)

EXTRA_DIST= test-gradient.c click.c docs.txt
