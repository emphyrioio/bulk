#  ________________________________________________________________________________________
# /\                                                                                       \
# \_| Run the commands stored in 'CMD' on some or all Python scripts in current directory. |
#   | * run all scripts : 'make' or 'make test' or 'make *.py'                             |
#   | * run one or more scripts : 'make file1.py file2.py...' or 'make file1 file2...'     |
#   |   ___________________________________________________________________________________|_
#    \_/_____________________________________________________________________________________/
   
EXT=py
FILES!=echo *.${EXT}
CMD=./

all: test

test: ${FILES}

.for file in ${FILES}
${file:R}: ${file}
.endfor

*.${EXT}::
        ${CMD}$@
