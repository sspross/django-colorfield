=================
django-colorfield
=================

Simple colorfield for django (optimized for grappelli)

Installation
============

Add `colorfield` to your `INSTALLED_APPS`.

Then in your models, you can use it like this::

    from django.db import models
    from colorfield.fields import ColorField


    class Show(ExtendedModel):
        title = models.CharField(u'Title', max_length=250)
        color = ColorField(default='ffffff')


    