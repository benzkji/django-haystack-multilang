# django-haystack-multilang

put your translated content into haystack, with ease. abstracting away the technical gotchas, making it easy to index in many languages, so you can focus on your content and index.

some concepts are from aldryn-haystack. but without the aldryn ecosystem dependencies.

provides a base multilang SearchIndex, as well as a contrib.djangocms_haystack_multilang, providing an index for django-cms.

## Quickstart

Installed apps?

Define your indexes, for each language one.

Setup your own SearchIndex, inheriting from `haystack_multilang.MultilangIndex`

Using django-cms? Add haystack_multilang.contrib.djangocms_haystack_multilang to installed apps.


## Define indexes in settings.py

You'll need a seperate haystack index for each language...


## Setup your own indexes

Describe how a multilangIndex works, how content for each language is fetched, etc.


## contrib.djangocms_haystack_multilang

Contrib package for django-cms. Describe settings, AppHook, etc.


## Do it!