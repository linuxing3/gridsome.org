---
title: using orgmode in emacs.org
author: Xing Wenju
date: 2020-03-03
excerpt: 
---

# Table of Contents

1.  [the super org is the module of emacs](#org79ccb44)

<a id="org79ccb44"></a>

# the super org is the module of emacs

Org-mode is a fabulous organizational tool originally built by Carsten
Dominik that operates on plain text files. Org-mode is part of Emacs.

This document assumes you&rsquo;ve had some exposure to org-mode already so
concepts like the agenda, capture mode, etc. won&rsquo;t be completely
foreign to you. More information about org-mode can be found in the
[Org-Mode Manual](http://orgmode.org/index.html#sec-4.1) and on the [Worg Site](http://orgmode.org/worg/).

I have been using org-mode as my personal information manager for
years now. I started small with just the default `TODO` and `DONE`
keywords. I added small changes to my workflow and over time it
evolved into what is described by this document.

I still change my workflow and try new things regularly. This
document describes mature workflows in my current org-mode setup. I
tend to document changes to my workflow 30 days after implementing
them (assuming they are still around at that point) so that the new
workflow has a chance to mature.

Some of the customized Emacs settings described in this document are
set at their default values. This explicitly shows the setting for
important org-mode variables used in my workflow and to keep my
workflow behaviour stable in the event that the default value changes
in the future.

This document is available as an [org file](http://doc.norang.ca/org-mode.org) which you can load in Emacs
and tangle with `C-c C-v C-t` which will create org-mode.el in the
same directory as the org-mode.org file. This will extract all of the
elisp examples in this document into a file you can include in your
.emacs file.
