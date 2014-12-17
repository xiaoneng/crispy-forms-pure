.. _docutils: http://docutils.sourceforge.net/
.. _Django: https://www.djangoproject.com/
.. _django-crispy-forms: https://github.com/maraujop/django-crispy-forms
.. _pure: http://github.com/zurb/pure
.. _pure Grid: http://pure.zurb.com/docs/grid.php
.. _crispy-forms-pure-demo: https://github.com/sveetch/crispy-forms-pure-demo
.. _Abide: http://pure.zurb.com/docs/components/abide.html

Introduction
============

This is a `Django`_ application to add `django-crispy-forms`_ layout objects for `pure`_.

This app does not embed a `pure`_ release, you will have to install it yourself.

Links
*****

* Read the documentation on `Read the docs <http://crispy-forms-pure.readthedocs.org/>`_;
* Download his `PyPi package <http://pypi.python.org/pypi/crispy-forms-pure>`_;
* Clone it on his `Github repository <https://github.com/sveetch/crispy-forms-pure>`_;
* Demo app : `crispy-forms-pure-demo`_;

Requires
========

* `django-crispy-forms`_ = 1.4.x;

Installation
============

Just register the app in your project settings like that :

.. sourcecode:: python

    INSTALLED_APPS = (
        ...
        'crispy_forms',
        'crispy_forms_pure',
        ...
    )

Then append this part to specify usage of the pure set :

.. sourcecode:: python

    # Default layout to use with "crispy_forms"
    CRISPY_TEMPLATE_PACK = 'pure'

If not defined, the default template pack name used is ``pure``, also there is a basic ``pure`` support but it's not be maintained anymore.

All other `django-crispy-forms`_ settings option apply, see its documentation for more details.
