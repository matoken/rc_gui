uidir = $(datadir)/rc_gui

ui_in_files = rc_gui.ui
	
ui_DATA = $(ui_in_files)

desktopdir=$(datadir)/applications

desktop_in_files= \
	rc_gui.desktop.in \
	$(NULL)
desktop_DATA = $(desktop_in_files:.desktop.in=.desktop)
@INTLTOOL_DESKTOP_RULE@

EXTRA_DIST = $(ui_in_files) \
			$(desktop_in_files) \
			$(desktop_DATA) \
			$(NULL)
