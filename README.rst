Packages
========

This is just a scratchboard for a possible distributed packaging system
for Python.

Package servers can be treated like Git remotes. Pull a package from one,
push it to another.


Components
----------

- Flask-powered PyPi-compatible server. Authentication.
- A CLI client.


Ummm.. Why?
-----------

I've spent 3 hours today trying to deal with some deep dependency of
someone's broken package. I want this to take seconds.

I want:

- Simple nested requirements overrides
- Simple-as-humanely possible private mirroring
- backwards compatibility w/ pip/easy_install, or something.
