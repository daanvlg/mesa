include $(top_srcdir)/src/gallium/Automake.inc

noinst_LTLIBRARIES = libtegra.la

AM_CPPFLAGS = \
	-I$(top_srcdir)/src/gallium/drivers/tegra/include \
	-I$(top_srcdir)/src/gallium/drivers \
	-I$(top_srcdir)/include

AM_CFLAGS = \
	$(GALLIUM_CFLAGS) \
	$(LIBDRM_CFLAGS)

libtegra_la_SOURCES = \
	tegra_context.c \
	tegra_context.h \
	tegra_resource.c \
	tegra_resource.h \
	tegra_screen.c \
	tegra_screen.h \
	tegra_state.c \
	tegra_state.h \
	tegra_surface.c \
	tegra_surface.h
