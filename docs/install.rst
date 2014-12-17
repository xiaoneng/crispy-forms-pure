.. _django-crispy-forms: https://github.com/maraujop/django-crispy-forms
.. _pure: http://github.com/zurb/pure
.. _crispy-forms-pure-demo: https://github.com/sveetch/crispy-forms-pure-demo

=======
Install
=======

Register the app in your project settings like that :

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

If not defined, the default template pack name used is ``pure``, also you can use ``pure`` but pay attention that is not really maintained.

All other `django-crispy-forms`_ settings option apply, see its documentation for more details.
