ACLOCAL_AMFLAGS = -I m4

if MAKE_DEMOS
  DEMO_DIR = demo
endif

if MAKE_UNITTEST
  UNITTEST_DIR = test
endif

SUBDIRS = src \
    src/unit \
    src/http \
    src/xmlrpc \
    src/bin \
    src/json \
    include \
    $(DEMO_DIR) $(UNITTEST_DIR)

bin_SCRIPTS = cxxtools-config

pkgconfigdir = $(libdir)/pkgconfig/

pkgconfig_DATA = pkgconfig/cxxtools-bin.pc \
	pkgconfig/cxxtools-http.pc \
	pkgconfig/cxxtools-json.pc \
	pkgconfig/cxxtools.pc \
	pkgconfig/cxxtools-unit.pc \
	pkgconfig/cxxtools-xmlrpc.pc

EXTRA_DIST = \
	Releasenotes-2.2.markdown
