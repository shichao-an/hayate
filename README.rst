Hayate
======

Hayate (はやて) is a simple tool to monitor logged in users. It sent an email when the targeted user logs in.

It is named after `Hayate Yagami <http://ja.wikipedia.org/wiki/%E5%85%AB%E7%A5%9E%E3%81%AF%E3%82%84%E3%81%A6>`_.

Dependencies
------------

* GNU Screen
* Mutt

Usage
-----

Start monitoring:

::

    $ hayate username yourname@example.com

Check screen session:

::

    $ screen -ls

Stop monitoring by quiting the session:

::

    $ screen -X -S hayate-session quit
