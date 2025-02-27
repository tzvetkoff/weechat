#
# Copyright (C) 2003-2022 Sébastien Helleu <flashcode@flashtux.org>
#
# This file is part of WeeChat, the extensible chat client.
#
# WeeChat is free software; you can redistribute it and/or modify
# it under the terms of the GNU General Public License as published by
# the Free Software Foundation; either version 3 of the License, or
# (at your option) any later version.
#
# WeeChat is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
# GNU General Public License for more details.
#
# You should have received a copy of the GNU General Public License
# along with WeeChat.  If not, see <https://www.gnu.org/licenses/>.
#

AM_CPPFLAGS = -DLOCALEDIR=\"$(datadir)/locale\" $(GCRYPT_CFLAGS) $(GNUTLS_CFLAGS) $(CURL_CFLAGS) $(ZLIB_CFLAGS) $(ZSTD_CFLAGS)

noinst_LIBRARIES = lib_weechat_core.a

lib_weechat_core_a_SOURCES = weechat.c \
                             weechat.h \
                             wee-arraylist.c \
                             wee-arraylist.h \
                             wee-backtrace.c \
                             wee-backtrace.h \
                             wee-calc.c \
                             wee-calc.h \
                             wee-command.c \
                             wee-command.h \
                             wee-completion.c \
                             wee-completion.h \
                             wee-config.c \
                             wee-config.h \
                             wee-config-file.c \
                             wee-config-file.h \
                             wee-crypto.c \
                             wee-crypto.h \
                             wee-debug.c \
                             wee-debug.h \
                             wee-dir.c \
                             wee-dir.h \
                             wee-eval.c \
                             wee-eval.h \
                             wee-hashtable.c \
                             wee-hashtable.h \
                             wee-hdata.c \
                             wee-hdata.h \
                             wee-hook.c \
                             wee-hook.h \
                             wee-infolist.c \
                             wee-infolist.h \
                             wee-input.c \
                             wee-input.h \
                             wee-list.c \
                             wee-list.h \
                             wee-log.c \
                             wee-log.h \
                             wee-network.c \
                             wee-network.h \
                             wee-proxy.c \
                             wee-proxy.h \
                             wee-secure.c \
                             wee-secure.h \
                             wee-secure-buffer.c \
                             wee-secure-buffer.h \
                             wee-secure-config.c \
                             wee-secure-config.h \
                             wee-signal.c \
                             wee-signal.h \
                             wee-string.c \
                             wee-string.h \
                             wee-upgrade.c \
                             wee-upgrade.h \
                             wee-upgrade-file.c \
                             wee-upgrade-file.h \
                             wee-url.c \
                             wee-url.h \
                             wee-utf8.c \
                             wee-utf8.h \
                             wee-util.c \
                             wee-util.h \
                             wee-version.c \
                             wee-version.h \
                             hook/wee-hook-command-run.c \
                             hook/wee-hook-command-run.h \
                             hook/wee-hook-command.c \
                             hook/wee-hook-command.h \
                             hook/wee-hook-completion.c \
                             hook/wee-hook-completion.h \
                             hook/wee-hook-config.c \
                             hook/wee-hook-config.h \
                             hook/wee-hook-connect.c \
                             hook/wee-hook-connect.h \
                             hook/wee-hook-fd.c \
                             hook/wee-hook-fd.h \
                             hook/wee-hook-focus.c \
                             hook/wee-hook-focus.h \
                             hook/wee-hook-hdata.c \
                             hook/wee-hook-hdata.h \
                             hook/wee-hook-hsignal.c \
                             hook/wee-hook-hsignal.h \
                             hook/wee-hook-info-hashtable.c \
                             hook/wee-hook-info-hashtable.h \
                             hook/wee-hook-info.c \
                             hook/wee-hook-info.h \
                             hook/wee-hook-infolist.c \
                             hook/wee-hook-infolist.h \
                             hook/wee-hook-line.c \
                             hook/wee-hook-line.h \
                             hook/wee-hook-modifier.c \
                             hook/wee-hook-modifier.h \
                             hook/wee-hook-print.c \
                             hook/wee-hook-print.h \
                             hook/wee-hook-process.c \
                             hook/wee-hook-process.h \
                             hook/wee-hook-signal.c \
                             hook/wee-hook-signal.h \
                             hook/wee-hook-timer.c \
                             hook/wee-hook-timer.h

EXTRA_DIST = CMakeLists.txt
