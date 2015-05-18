---
layout: post
title: Exaile is upgrading to GStreamer 1.x / GTK3!
---

GStreamer 0.10 has been obsolete for a long time now, and with the [impending removal of 0.10 from Debian](https://lists.debian.org/debian-devel/2015/05/msg00335.html) we decided that it would make sense to upgrade. PyGI for GStreamer 1.x is not compatible with GTK2, so we're upgrading to GTK3 at the same time. We're optimistic that the Exaile experience will be better than ever after these upgrades.

Due to the amount of work required, we're suspending work on non-critical bugs on the 3.4.x series until we've merged this into master.

Right now, we need people interested in playing around with gtk/gstreamer to poke at Exaile interface, see what breaks, record bugs, and issue pull requests to fix bugs. A lot of the heavy lifting has been done already and it sorta works, but there's still a lot left. Every little bit helps. If you want to mess with it, [check out the 'gi' branch on github](https://github.com/exaile/exaile/tree/gi).

At the moment, we're tracking things using [this wiki page](https://github.com/exaile/exaile/wiki/PyGI-migration-tasklist-%28GTK3-GStreamer-1.x%29). We're also hanging out on IRC at various times.

Once the bugs become much harder to find, we'll make a release candidate available for users to try it out, and track bugs using the github issue tracker. With your help, optimistically we can get this done in a few weeks.

Thanks for continuing to support Exaile!