# Sun-$Revision: 30.8 $
 
# Copyright 1994-2006 Sun Microsystems, Inc. and Stanford University.
# See the LICENSE file for license information.

ROOT         = ../..

FILES        = Makefile \
               stat_glue.cpp \
	       termcap_glue.cpp \
	       transcendental_glue.cpp \
               xgl_glue.cpp xgl.self \
	       xlib_glue.cpp 

OBJECT_FILES = stat.primMaker.hh \
	       termcap.primMaker.hh \
	       transcendental.primMaker.hh \
	       unixPrims.primMaker.hh \
	       xgl.primMaker.hh \
	       xlib.primMaker.hh \
	       \
	       macPrims.primMaker.hh \
	       macToolbox.primMaker.hh \

SELF_MODULES = primitiveMaker \
               stat_wrappers statTemplates \
	       termcap_wrappers termcapTemplates \
	       transcendental_wrappers transcendentalTemplates \
               unixPrims_wrappers unixPrimTemplates \
	       xgl_wrappers xglTemplates \
	       xlib_wrappers xlibTemplates \
	       \
	       macPrims_wrappers macPrimTemplates \
	       macToolbox_wrappers macToolboxTemplates \

DIRECTORIES  = sun4 svr4 mac_osx

include        ${ROOT}/templates/sources.make
