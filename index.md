---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
title: works-everywhere.org
---

## What are environmental bugs?

An application's environment is the hardware, software, files,
and communications it depends upon in order to get its job done.
Environmental bugs are bugs caused by differences between the
environments in which a multi-platform application should be able
to run.

## Why is this important?
Environmental bugs are sneaky.  It isn't feasible to test
software under every environment in which it is in which it is
expected to run.  This means bugs are only caught after software
fails once it has been delivered to its users.  At this point
its too late because [these bugs can cause real damage](https://github.com/valvesoftware/steam-for-linux/issues/3671)

## How?
Our goal is to construct tools that help developers more easily
identify when their software may be vulnerable to anomalous
environments.  First, this means tools that can analyze an
application at rest or in action in order to provide feedback
about how an application might be vulnerable.  Second, this
means tools that can easily and efficiently simulate weird
environments in order to prove that an application fails as
predicted so effort is not wasted on false positives.

We welcome pull requests for this site on [GitHub](https://github.com/works-everywhere/works-everywhere.github.io)
