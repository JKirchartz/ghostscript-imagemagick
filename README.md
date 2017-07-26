Ghostscript-Imagemagick
==================

ImageMagick® is a software suite to create, edit, compose, or convert bitmap images.

GhostScript® is an interpreter for the PostScript language and for PDF.

Requirements
------------

This role requires a debian compliant system such as ubuntu.

Role Variables
--------------

No variables

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: JKirchartz.ghostscript-imagemagick }

Tasks
-----

  - Install [GhostScript](https://www.ghostscript.com/)
  - Install [ImageMagick](http://www.imagemagick.org/)

License
-------

BSD
