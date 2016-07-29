Emacs configuration of Alexander Lenz
=====================================

Personal emacs configuration. Originally forked from birkenfeld/.emacs.d.

**Purpose of subdirectories/files**

- ``early_startup.el``: code that gets run very early (before setup etc)
- ``late_startup.el``: code that gets run very late (after session init)
- ``setup``: code that gets run on initialization of emacs
- ``local-setup``: not in the repository; code that gets run on init
- ``lisp``: my own lisp libraries, or single-file libraries not on ELPA
- ``ext-lisp``: third-party large lisp libraries not on ELPA
- ``themes``: lisp files that contain color themes
- ``elpa``: third-party lisp libraries installed from ELPA
- ``saved``: will contain all files/dirs with saved stuff/caches created by emacs
