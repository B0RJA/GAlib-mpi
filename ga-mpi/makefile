# -*- Mode: makefile -*-
# Copyright (c) 1994-1996 Massachusetts Institute of Technology
# Copyright (c) 1996-2005 Matthew Wall
# -----------------------------------------------------------------------------

include ../makevars
include makefile.sources

INC_DIRS= -I..

.SUFFIXES: .C
.C.o:
	$(CXX) $(CXXFLAGS) $(INC_DIRS) -c $<

$(LIB): $(OBJS) 
	$(PRELINK)
	$(AR) $(LIB) $?
.C.a:;

clean:
	$(RM) $(LIB) BUILD
	$(RM) *.o *~ .#* *.bak core ii_files ptrepository

# DO NOT DELETE THIS LINE -- make depend depends on it.
