The current WebMark2_uml.png is generated with graph_models, a Django extension using the following command:
`python manage.py graph_models -a --disable-abstract-fields -o WebMark2_uml.png`

The command above requires the next packages to be installed through pip: graphviz, django-extensions and pydotplus.

You can filter the models drawn with the flag -I, for example `-I Result,Run*`.

Instructions on how to install and use graph_models can be found behind the following links:

https://simpleit.rocks/python/django/generate-uml-class-diagrams-from-django-models/

https://django-extensions.readthedocs.io/en/latest/graph_models.html
