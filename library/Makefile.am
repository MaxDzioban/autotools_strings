AM_CPPFLAGS = -I$(top_srcdir)/library
#cтатична бібліотека
lib_LIBRARIES = libmystring.a
libmystring_a_SOURCES = mystring.cpp

#динамічна бібліотека
lib_LTLIBRARIES = libmystring.la
libmystring_la_SOURCES = mystring.cpp mystring.hpp
#правила для динамічної бібліотеки
libmystring_la_LDFLAGS = -shared
libmystring_la_CXXFLAGS = -fPIC
