ACLOCAL_AMFLAGS = -I m4

SUBDIRS = component1 component2

rpms srcrpm:
	for dir in $(SUBDIRS); do \
		$(MAKE) -C $$dir $@; \
	done

.PHONY: rpms srcrpm


