+++
title = "Shortcodes"
description = "Information about the shortcodes supported by the Daisy theme."
date = "2025-03-07"
authors = ["Adrian Winterstein"]
+++

The Daisy theme adds certain [shortcodes](https://www.getzola.org/documentation/content/shortcodes/) that you can use in the markdown files of your website.

## Badges

```jinja2
{%/* badge_info(icon=true) */%}This is an info text.{%/* end */%}
{%/* badge_success(icon=true) */%}This is a success text.{%/* end */%}
{%/* badge_warning(icon=true) */%}This is a warning text.{%/* end */%}
{%/* badge_error(icon=true) */%}This is an error text.{%/* end */%}
```

Which would be rendered like this:
{% badge_info(icon=true) %}This is an info text.{% end %}
{% badge_success(icon=true) %}This is a success text.{% end %}
{% badge_warning(icon=true) %}This is a warning text.{% end %}
{% badge_error(icon=true) %}This is an error text.{% end %}

```jinja2
{%/* badge_primary() */%}This is a badge with the primary theme color.{%/* end */%}
{%/* badge_secondary() */%}This is a badge with the secondary theme color.{%/* end */%}
{%/* badge_accent() */%}This is a badge with the accent theme color.{%/* end */%}
{%/* badge_neutral() */%}This is a badge with the neutral theme color.{%/* end */%}
```

{% badge_primary() %}This is a badge with the primary theme color.{% end %}
{% badge_secondary() %}This is a badge with the secondary theme color.{% end %}
{% badge_accent() %}This is a badge with the accent theme color.{% end %}
{% badge_neutral() %}This is a badge with the neutral theme color.{% end %}
