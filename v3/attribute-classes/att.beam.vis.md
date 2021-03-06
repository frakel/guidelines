---
layout: sidebar
sidebar: s1
version: "v3"
title: "att.beam.vis"
---
<div class="classSpec att">
   <h3 id="att.beam.vis">att.beam.vis</h3>
   <table class="wovenodd">
      <tr>
         <td colspan="2" class="wovenodd-col2">Visual domain attributes.</td>
      </tr>
      <tr>
         <td class="wovenodd-col1"><strong>Module</strong></td>
         <td class="wovenodd-col2">MEI.cmn</td>
      </tr>
      <tr>
         <td class="wovenodd-col1"><strong>Members</strong></td>
         <td class="wovenodd-col2">
            <div class="parent">
               <div><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/beam.html">beam</a> (direct member of att.beam.vis)
               </div>
               <div><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/beamspan.html">beamSpan</a><span> (via <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.beamspan.vis.html">att.beamSpan.vis</a>)</span></div>
            </div>
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1"><strong>Attributes</strong></td>
         <td class="wovenodd-col2">
            <div class="attributeDef"><span class="attribute"><strong>@color</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Used to indicate visual appearance. Do not confuse this with the musical term
                  'color' as used in pre-CMN notation.</span>
               Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.color.html">data.COLOR</a>.
               <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.color.html">att.color</a></span></div>
            <div class="attributeDef"><span class="attribute"><strong>@form</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Captures whether a beam is "feathered" and in which direction.</span>
               Allowed values are:
               "<span style="font-weight: 500;">acc</span>" <i>((accelerando) indicates that the secondary beams get progressively closer
                  together toward the end of the beam.)</i>,  "<span style="font-weight: 500;">mixed</span>" <i>((mixed acc and rit) for beams that are "feathered" in both directions.)</i>,  "<span style="font-weight: 500;">rit</span>" <i>((ritardando) means that the secondary beams become progressively more distant
                  toward the end of the beam.)</i>,  "<span style="font-weight: 500;">norm</span>" <i>((normal) indicates that the secondary beams are equidistant along the course of
                  the beam.)</i><span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.beamrend.html">att.beamrend</a></span></div>
            <div class="attributeDef"><span class="attribute"><strong>@slope</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Records the slope of the beam.</span>
               Value of datatype <span style="font-weight: 500;">decimal</span>.
               <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.beamrend.html">att.beamrend</a></span></div>
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1"><strong>Declaration</strong></td>
         <td class="wovenodd-col2">
            <div class="code" xml:space="preserve" data-lang="ODD"><code>
                  <div class="indent1 indent"><span data-indentation="1" class="element">&lt;classes&gt;</span>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;memberOf
                           <span class="attribute">key=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.color.html">att.color</a>"</span></span>/&gt;</span></div>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;memberOf
                           <span class="attribute">key=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.beamrend.html">att.beamrend</a>"</span></span>/&gt;</span></div>
                     <span data-indentation="1" class="element">&lt;/classes&gt;</span></div></code></div>
         </td>
      </tr>
   </table>
</div>