Packages Client
================

I am:

- Stupidly simple to use
- Not tied to a single server
- Treat servers like git remotes
- Able to mirror projects from one source to another
- PyPi-compatible
- SSH Authenticated
- Centeralized server alias list


Potential Usage
---------------

Install 'requests' from PyPi ::

    $ packages install pypi/requests

Mirror PyPi 'requests' package to personal server ::

    $ packages mirror pypi/requests kr
    # if requests had dependencies, push them up too.
