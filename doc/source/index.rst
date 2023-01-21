..
   To set up for standalone development:

   In the "doc/" directory:

      python3 -m venv venv
      source venv/bin/activate
      pip install --upgrade pip
      pip install -r requirements_dev.txt

   Then, within "doc/" directory,

      sphinx-autobuild --re-ignore '/\.#' source build/html

   will launch a live-reload server to view the results.  See the developer docs
   for the pytch-website repository for how to build these docs into the main
   website docs.


The Pytch media library
=======================

.. caution::

   This index will not appear in the final website documentation.  It is just
   for standalone development of the media library docs.

.. toctree::
   :maxdepth: 2
   :caption: Contents:

   user/index
   developer/index
