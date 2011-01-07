Overview
========

Bootstrap
---------

First you need to bootstrap::

  python2.6 bootstrap.py -dc development.cfg
  bin/buildout c development.cfg

And add the default user::

  bin/addzope2user admin admin

This must correspond to the user / password noted in `etc/passwd`.

Run
---

To run a Zope server, use::

  bin/paster serve etc/zope.ini
