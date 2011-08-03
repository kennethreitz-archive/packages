Packages
========

This is just a scratchboard for a possible distributed packaging system
for Python.

Package servers can be treated like Git remotes. Pull a package from one,
push it to another.


**Components:**

- `Server <https://github.com/kennethreitz/packages/tree/master/packages-server>`_
- `Client <https://github.com/kennethreitz/packages/tree/master/packages-client>`_


Goals
-----

I've spent 3 hours today trying to deal with some deep dependency of
someone's broken package. This should take seconds.

- Mirror (or fork) any project in mere seconds
- PyPi + Pip compatibility
- Dependencies managed by installer (packages client), not distutils.


Users
------

- Everyone. PyPi Alternative
- Companies. Shouldn't rely on third parties.
- Open source projects. Shouldn't rely on third parties.
