# scim

* Homepage: https://github.com/andmarti1424/scim

Smart Common Input Method (SCIM) is an input method (IM) platform.  Input
 methods are needed to enter complex characters in many non-latin
 languages. SCIM provides a common platform for various plugin modules and
 independent IM programs, as well as a set of modules and programs on its
 own.  It is highly modularized and exposes abstract interfaces, so that
 plugin modules with different functions can easily communicate with each
 other.  The currently supported module types are configuration, IM engine,
 front end, filter, and setup GUI.

 SCIM achieves the communication between IM engines and front ends through
 both shared library linking and server/client mode.  It supports XIM
 protocol, as well as GTK+ IM module and Qt IM module.

 This package is the main binary package of SCIM.  It includes: the main
 program scim (GTK+ based) and other support programs; simple configuration
 module, X11 front end module, rawcode IM engine module,
 simplified/traditional Chinese conversion filter module, and their
 corresponding setup GUI modules; GTK+ panel and its setup GUI module; and
 a GTK+ based setup tool.

 SCIM is a well accepted platform and features various input method engines
 for many languages.  In Debian you can find the following separately
 packaged IMs useful: scim-tables-{additional,ja,ko,zh}, scim-pinyin, scim-
 uim, scim-m17n, scim-chewing, scim-anthy, scim-canna, scim-prime, and
 scim-skk. GTK+ users would also find package scim-gtk-immodule useful for
 GTK+ IM module support.

 For development on SCIM platform, please see the description of scim-dev
 package.
