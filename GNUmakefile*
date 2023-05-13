CMD := ./
SCRIPTS := $(basename $(wildcard *.py))

all: test

.PHONY: test
test: $(SCRIPTS)

%: %.py
	$(CMD)$<
