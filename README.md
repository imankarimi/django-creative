:warning: Warning!!
> Before Django 1.8 you should specify context processors different way. Also use ``django.core.context_processors.request`` instead of ``django.template.context_processors.request``.

```python
    from django.conf import global_settings

    TEMPLATE_CONTEXT_PROCESSORS = global_settings.TEMPLATE_CONTEXT_PROCESSORS + (
        'django.core.context_processors.request',
    )
```
