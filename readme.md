# Multicolumn element

A two-column element with defineable width

# Config

Defaults are column widths 1-12.

The second column is calculated from maximum minus set.

Config from yml:

```yaml
---
name: multicolumn-config
---
Firesphere\MultiColumn\Elements\MultiColumnElement:
  config:
    start: 1
    end: 12

```