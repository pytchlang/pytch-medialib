Pytch media library (developer notes)
=====================================

We provide users with a library of media for use in their projects.
Currently, the library consists just of assets used in our tutorials.
We plan to add other selected media in the future.


Structure of the library
------------------------

An ``index.json`` file describes the media files which are available.
Each is identified by a content-hash and has a name and a list of
tags.  The webapp allows the user to filter by tag/s.


Tutorial media
--------------

These are gathered from the ``pytch-tutorials`` repo using a utility
in the ``pytch-build`` repo.


Serving the media library
-------------------------

For local development, the library is served from the ``dist``
directory within the ``pytch-medialib`` repo.  When building a
deployment, the media library lives in
``medialib/$PYTCH_DEPLOYMENT_ID``.
