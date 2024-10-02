# шлях до заголовкових файлів
AM_CPPFLAGS = -I$(top_srcdir)/library

bin_PROGRAMS = own_tests
own_tests_SOURCES = own_tests.cpp

#лінкування з бібліотекою
own_tests_LDADD = $(top_builddir)/library/libmystring.la

