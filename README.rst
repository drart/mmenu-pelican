mmenu-pelican
-------------


This theme integrates the fantastic `mmenu <http://mmenu.frebsite.nl/>`_ framework with Pelican.

Pages contain a background animation that was prototyped with `Processing.js <http://processingjs.org>`_  and then converted to simple Canvas calls.

Settings
~~~~~~~~

Additional setting used by this theme, if present:

::

    BLOG_TITLE = string

``BLOG_TITLE`` is the title that will appear at the top of the blog section of the website. ``SITE_TITLE`` will appear on pages but not on the blog.

::

    WORK_TITLE = string

If ``WORK_TITLE`` is present then a section header is added to the naviagation menu. I use this to separate my art works from the more general sections of my site.

::

    WORK_LINKS = [ [string,URL] [string,URL], ...] 

``WORK_LINKS`` is an array of string + URL pairs in the style of ``SITE_LINKS`` that goes under the ``WORK_TITLE`` section.


TODO
~~~~

- probably lots
