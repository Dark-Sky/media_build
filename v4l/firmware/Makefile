# This file implements the GNOME Build API:
# http://people.gnome.org/~walters/docs/build-api.txt

FIRMWAREDIR = /lib/firmware

all:

check:

install:
	mkdir -p $(FIRMWAREDIR)
	cp -rv * $(FIRMWAREDIR)
	rm -rf $(FIRMWAREDIR)/usbdux
	find $(FIRMWAREDIR) \( -name 'WHENCE' -or -name 'LICENSE.*' -or \
		-name 'LICENCE.*' \) -exec rm -- {} \;
