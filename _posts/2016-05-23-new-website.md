---
layout: post
title:  New Website
date:   2016-05-23
---

Hi LUG,

If you've visited the LUG website in the last 24 hours, you may have noticed
that it looks a bit different. Well, that's because it's now a Jekyll site! Our
previous website was written in Django by old members, and had lots of cool
functionality, but it was integrated with LDAP (which we no longer use) and
when char...ah...overflowed! it stopped working. Not being a web developer or
familiar with Django, and no longer seeing a need for LDAP with our current
userload, I made the executive decision to move the site to something a bit
lighter and more maintainable that I've worked with before, so here we are.
Now that we have write access back on the site, you can expect to see updates
a bit more frequently than a year apart :)

Now that that's taken care of, we have a couple other tasks to take care of
before our infrastructure is up to speed. These are:

* Updating Short to the latest Ubuntu LTS (16.04 / Xenial Xerus)
* Imaging Char with the same.

Short's upgrade should be fairly painless, I just need to schedule some
downtime. I'm tentatively calling that Friday, May 28th, sometime in the
evening, open to discussion.

Char will require rack console access. If anyone's still in town and is
interested in helping, or wants to learn how to bring up a server from scratch,
shoot out an email to the mailing list saying when you're free and any
suggestions for infrastructure choices. We've decided on Ubuntu 16.04 for the
base system, but what we're actually going to use it for is still up in the
air. It's an older, less powerful system relative to Short, but it's still got
a beefy Xeon from a few years ago and a decent amount of memory to boot.

The server room is tightly access-controlled and there's not a lot of room
besides, so while I'd like to have a show-and-tell, this will need to be
performed by a minimal number of people. I don't think many people are in town
anyway so it shouldn't be a problem.
