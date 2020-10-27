# Copyright 2020 Lostest Ones
# SPDX-License-Identifier: BSD-3-Clause

CC:= gcc
CFLAGS:= -Wall -Wextra -Werror -Wno-unused-parameter -g -std=c11 
CPROTECT:= -DPROTECT
SOURCES:= race.c utils.c print.c

all: protect unprotect

protect: $(SOURCES) Makefile
	$(CC) $(CFLAGS) $(CPROTECT) $(SOURCES) -o protect
	
unprotect: $(SOURCES) Makefile
	$(CC) $(CFLAGS) $(SOURCES) -o unprotect

clean:
	$(RM) protect unprotect
