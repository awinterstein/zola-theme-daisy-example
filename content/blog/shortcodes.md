+++
title = "Shortcodes"
description = "Information about the shortcodes supported by the Daisy theme."
date = "2025-03-07"
authors = ["Adrian Winterstein"]
+++

The Daisy theme adds certain [shortcodes](https://www.getzola.org/documentation/content/shortcodes/) that you can use in the markdown files of your website.

## Badges

```jinja2
{%/* badge_info() */%}This is an info text.{%/* end */%}
{%/* badge_success() */%}This is a success text.{%/* end */%}
{%/* badge_warning() */%}This is a warning text.{%/* end */%}
{%/* badge_error() */%}This is an error text.{%/* end */%}
```

Which would be rendered like this:
{% badge_info() %}This is an info text.{% end %}
{% badge_success() %}This is a success text.{% end %}
{% badge_warning() %}This is a warning text.{% end %}
{% badge_error() %}This is an error text.{% end %}
