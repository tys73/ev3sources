SOURCES = c_ui.c d_lcd.c d_terminal.c

TARGET = libc_ui.so

CONF = Linuxlib
ARCH = X86

include ../../open_first/rules.mk

c_ui.o: | genimages
genimages:
	$(MAKE) -C ../../lmssrc/c_ui install
