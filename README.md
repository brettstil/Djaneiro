# Django support for Sublime Text 2/3

[![Join the chat at https://gitter.im/squ1b3r/Djaneiro](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/squ1b3r/Djaneiro?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

## Installation

Using [Package Control](https://packagecontrol.io/installation):

- Open the Command Pallete (`ctrl+shift+P` or `cmd+shift+P`).
- Type “Install Package” and hit return.
- Type “Djaneiro” and hit return.

## Snippets for Django templates

| Abbreviation   | Tag                                              |
|----------------|--------------------------------------------------|
| autoescape     | ``{% autoescape %} {% autoescape %}``            |
| block          | ``{% block %} {% endblock %}``                   |
| comment        | ``{% comment %} {% endcomment %}``               |
| csrf           | ``{% csrf_token %}``                             |
| cycle          | ``{% cycle %}``                                  |
| debug          | ``{% debug %}``                                  |
| ext            | ``{% extends "" %}``                             |
| extends        | ``{% extends "" %}``                             |
| filter         | ``{% filter %} {% endfilter %}``                 |
| firstof        | ``{% firstof %}``                                |
| for            | ``{% for in %} {% endfor %}``                    |
| fore           | ``{% for in %} {% empty %} {% endfor %}``        |
| if             | ``{% if %} {% endif %}``                         |
| ifchanged      | ``{% ifchanged %} {% endifchanged %}``           |
| ife            | ``{% if %} {% else %} {% endif %}``              |
| ifelse         | ``{% if %} {% else %} {% endif %}``              |
| ifeq           | ``{% ifequal %} {% endifequal %}``               |
| ifequal        | ``{% ifequal %} {% endifequal %}``               |
| ifnotequal     | ``{% ifnotequal %} {% endifnotequal %}``         |
| inc            | ``{% include %}``                                |
| include        | ``{% include %}``                                |
| load           | ``{% load %}``                                   |
| now            | ``{% now "" %}``                                 |
| regroup        | ``{% regroup by as %}``                          |
| spaceless      | ``{% spaceless %} {% endspaceless %}``           |
| ssi            | ``{% ssi %}``                                    |
| static         | ``{% static %}``                                 |
| templatetag    | ``{% templatetag %}``                            |
| url            | ``{% url %}``                                    |
| verbatim       | ``{% verbatim %} {% endverbatim %}``             |
| widthratio     | ``{% widthratio %}``                             |
| with           | ``{% with as %} {% endwith %}``                  |
| trans          | ``{% trans %}``                                  |
| blocktrans     | ``{% blocktrans with as %} {% endblocktrans %}`` |

...and some non-official stuff:

| Abbreviation | Tag                                                   |
|--------------|-------------------------------------------------------|
| super        |  ``{{ block.super }}``                                |
| extrahead    |  ``{% block extrahead %} {% endblock extrahead %}``   |
| extrastyle   |  ``{% block extrastyle %} {% endblock extrastyle %}`` |
| var          |  ``{{ }}``                                            |
| tag          |  ``{% %}``                                            |
| staticu      |  ``{{ STATIC_URL }}``                                 |
| media        |  ``{{ MEDIA_URL }}``                                  |

## Snippets for Django model fields

| Abbreviation | Tag                                     |
|--------------|-----------------------------------------|
| mauto        | ``models.AutoField()``                  |
| mbigint      | ``models.BigIntegerField()``            |
| mbool        | ``models.BooleanField()``               |
| mchar        | ``models.CharField()``                  |
| mcoseint     | ``models.CommaSeparatedIntegerField()`` |
| mdate        | ``models.DateField()``                  |
| mdatetime    | ``models.DateTimeField()``              |
| mdecimal     | ``models.DecimalField()``               |
| mduration    | ``models.DurationField()``              |
| memail       | ``models.EmailField()``                 |
| mfile        | ``models.FileField()``                  |
| mfilepath    | ``models.FilePathField()``              |
| mfloat       | ``models.FloatField()``                 |
| mimg         | ``models.ImageField()``                 |
| mint         | ``models.IntegerField()``               |
| mip          | ``models.IPAddressField()``             |
| mnullbool    | ``models.NullBooleanField()``           |
| mphone       | ``models.PhoneNumberField()``           |
| mposint      | ``models.PositiveIntegerField()``       |
| mpossmallint | ``models.PositiveSmallIntegerField()``  |
| mslug        | ``models.SlugField()``                  |
| msmallint    | ``models.SmallIntegerFiled()``          |
| mtext        | ``models.TextField()``                  |
| mtime        | ``models.TimeField()``                  |
| murl         | ``models.URLField()``                   |
| musstate     | ``models.USStateField()``               |
| muuid        | ``models.UUIDField()``                  |
| mxml         | ``models.XMLField()``                   |
| fk           | ``models.ForeignKey()``                 |
| m2m          | ``models.ManyToManyField()``            |
| o2o          | ``models.OneToOneField()``              |


## Snippets for Django form fields

| Abbreviation | Code                                 |
|--------------|--------------------------------------|
| fchar        | ``forms.CharField()``                |
| fchoice      | ``forms.ChoiceField()``              |
| fcombo       | ``forms.ComboField()``               |
| fdate        | ``forms.DateField()``                |
| fdatetime    | ``forms.DateTime()``                 |
| fdecimal     | ``forms.DecimalField()``             |
| fduration    | ``forms.DurationField()``            |
| femail       | ``forms.EmailField()``               |
| ffile        | ``forms.FileField()``                |
| ffilepath    | ``forms.FilePathField()``            |
| ffloat       | ``forms.FloatField()``               |
| fimg         | ``forms.ImageField()``               |
| fint         | ``forms.IntegerField()``             |
| fip          | ``forms.IPAddressField()``           |
| fmochoice    | ``forms.ModelChoiceField()``         |
| fmomuchoice  | ``forms.ModelMultipleChoiceField()`` |
| fmuchoice    | ``forms.MultipleChoiceField()``      |
| fmuval       | ``forms.MultipleValueField()``       |
| fnullbool    | ``forms.NullBooleanField()``         |
| fregex       | ``forms.RegexField()``               |
| fslug        | ``forms.SlugField()``                |
| fsdatetime   | ``forms.SplitDateTime()``            |
| ftime        | ``forms.TimeField()``                |
| ftchoice     | ``forms.TypedChoiceField()``         |
| ftmuchoice   | ``forms.TypedMultipleChoiceField()`` |
| furl         | ``forms.URLField()``                 |
| fuuid        | ``forms.UUIDField()``                |

## Snippets for Django Views

| Abbreviation     | Code                                 |
|------------------|--------------------------------------|
| view             | ``Function Based View``              |
| createview       | ``Generic Create View``              |
| updateview       | ``Generic Update View``              |
| deleteview       | ``Generic Delete View``              |
| detailview       | ``Generic Detail View``              |
| listview         | ``Generic List View``                |
| templateview     | ``Generic Template View``            |
| adminview        | ``Generic Admin View``               |
| tabularinline    | ``Tabular Inline View``              |
| stackedinline    | ``Stacked Inline View``              |
| dispatch         | ``dispatch method for CBVs``         |
| get_context_data | ``get_context_data method for CBVs`` |

## Snippets for Django Models

| Abbreviation     | Code                                 |
|------------------|--------------------------------------|
| Model            | ``Simple Model Class``               |
| Model_full       | ``Full Model Class(with TODOs)``     |

## Snippets for Python

| Abbreviation | Code                                              |
|--------------|---------------------------------------------------|
| __init__     | ``__init__(self, *args, **kwargs)``               |
| pdb          | ``import pdb ; pdb.set_trace()``                  |
| ipdb         | ``import ipdb ; ipdb.set_trace()``                |
| npdb         | ``from nose.tools import set_trace; set_trace()`` |
| traceback    | ``import traceback; traceback.print_exc();``      |
| utfc         | ``coding: utf-8 ``                                |

## Completions

| Abbreviation          |
|-----------------------|
| `null`                |
| `blank`               |
| `choices`             |
| `db_column`           |
| `db_index`            |
| `db_tablespace`       |
| `default`             |
| `related_name`        |
| `editable`            |
| `error_message`       |
| `help_message`        |
| `primary_key`         |
| `unique`              |
| `unique_together`     |
| `unique_for_date`     |
| `unique_for_month`    |
| `unique_for_year`     |
| `verbose_name`        |
| `verbose_name_plural` |
| `validators`          |
| `auto_now_add`        |
| `auto_now`            |
| `required`            |
| `label`               |
| `initial`             |
| `widget`              |
| `localized`           |
| `return`              |
| `RequestContext`      |
| `context_instance`    |
| `render_to_response`  |
| `render`              |
| `redirect`            |
| `get_object_or_404`   |
| `get_list_or_404`     |
