=====
Must
=====

must is a simple Django app build for a university in Kenya, Meru University of Science and Technology(MUST) to find lost Items within the Campus premises. It's a Lost/Found App. It's still under development.

Detailed documentation is in the "docs" directory.

Quick start
-----------

1. Add "must" to your INSTALLED_APPS setting like this::

    INSTALLED_APPS = [
        ...
        'must',
    ]

2. Include the must URLconf in your project urls.py like this::

    path('must/', include('must.urls')),

3. Run `python manage.py migrate` to create the must models.

4. Start the development server and visit http://127.0.0.1:8000/admin/
   to create an item (you'll need the Admin app enabled).

5. Visit http://127.0.0.1:8000/must/ to view lost and found items.