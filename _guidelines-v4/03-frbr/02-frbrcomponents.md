---
sectionid: FRBRcomponents
title: "Component Parts in MEI"
version: "v3"
---

Each of the four MEI elements corresponding to FRBR entities may contain a list of
constituent parts. All four entities utilize the same element:



{% include desc elem="componentgrp" %}




However, the child elements of a component group must be the same type as the group's
parent.
This allows for a more detailed description than is possible using the core MEI {% include link elem="contents" %} element. For example, a work element’s {% include link elem="componentgrp" %} element can only contain {% include link elem="work" %} elements, etc. In
this way, the {% include link elem="componentgrp" %} element may be employed to describe composite
works, as in the example below:

{% include plainExample.html example="examples/frbr/frbr-sample083.xml" valid="true" version=page.version %}
This technique can also be applied when a single intellectual source is comprised
of multiple
physical parts. In the following example, the choral parts were published in four
physically
separate "signatures":

{% include plainExample.html example="examples/frbr/frbr-sample084.xml" valid="true" version=page.version %}