
AUTOMAKE_OPTIONS = serial-tests

noinst_PROGRAMS = test-noise

test_noise_SOURCES = \
	test-cipherstate.c \
	test-dhstate.c \
	test-errors.c \
	test-handshakestate.c \
	test-hashstate.c \
	test-main.c \
	test-names.c \
	test-patterns.c \
	test-randstate.c \
	test-signstate.c \
	test-symmetricstate.c

AM_CPPFLAGS = -I$(top_srcdir)/include -I$(top_srcdir)/src
AM_CFLAGS = @WARNING_FLAGS@

LDADD = ../../src/protocol/libnoiseprotocol.a

TESTS = $(noinst_PROGRAMS)