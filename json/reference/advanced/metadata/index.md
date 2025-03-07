---
title: Metadata
---

{:toc}
- TOC

Metadata is information about objects or properties (e.g. the source or security level of the information).

## Schema example

Here is an example of NIEM metadata associated with the object `nc:Case` in a JSON schema:

```json
{% include_relative nc.schema.json %}
```

## Instance example

This schema references other schema: [xs](xs.schema.json) and [structures](structures.schema.json)

Here is a JSON instance of that metadata:

```json
{% include_relative metadata.json %}
```
