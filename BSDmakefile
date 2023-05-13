CMD= ./
SCRIPTS!=for f in *.py; do echo "$${f%.py}"; done

all: test

.PHONY: test
test: ${SCRIPTS}
	
.PHONY: ${SCRIPTS}
${SCRIPTS}:
	${CMD}$@.py
