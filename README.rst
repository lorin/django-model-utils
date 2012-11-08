==================
django-model-utils
==================

This is a fork of Carl Meyer's `django-model-utils`_ library.
The only change is that the InheritanceManager has been extended to support multiple levels of inheritance.

Unfortunately, this change does not work in current versions of Django due to `bug 16572`_.
However, there is a proposed fix attached to that ticket that resolves the problem.
You will need to apply that patch in order to use this version.

.. _django-model-utils: https://github.com/carljm/django-model-utils
.. _bug 16572: https://code.djangoproject.com/ticket/16572
