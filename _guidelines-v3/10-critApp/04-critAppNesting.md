---
sectionid: critAppNesting
title: Nesting Apparati
---


<h2 id="critAppNesting">
   <span class="headingNumber">10.4</span>
   <span class="head">Nesting Apparati</span>
</h2>
In some situations, musical sources will agree at one level while differing at a lower
level.
For these cases, 
<a class="link_odd_elementSpec" href="/v3/elements/app">app</a> elements may be nested to any level necessary. In
the following example, there are three sources, two of which agree on the addition
of a
measure, but differ in the content of the added measure:


{% include _plainExample.html example="./v3/examples/critApp/critApp-sample206.xml" valid="false" %}


When nesting 
<a class="link_odd_elementSpec" href="/v3/elements/app">app</a> elements, it is important that the value(s) in the
child 
<a class="link_odd_elementSpec" href="/v3/elements/rdg">rdg</a> element's **@source** attribute must be a strict subset
of the ancestor 
<a class="link_odd_elementSpec" href="/v3/elements/rdg">rdg</a> element's **@source** value.


<!-- TODO:
    <egXML xmlns="http://www.tei-c.org/ns/Examples" xml:space="preserve">
<!-\- NEED EXAMPLE HERE! -\->
<!-\- Show how *NOT* to do it, then an example of good practice -\->
    </egXML>-->
