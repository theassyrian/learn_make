.PHONY: all

# $(eval _text)

sources = foo.c bar.c baz.s ugh.h
$(eval sources := $(filter %.c %.s, $(sources)))

#@echo $(filter %.c %.s, foo.c bar.c baz.s h.h)

all:
	@echo $(sources)

