---
layout: sidebar
sidebar: s1
version: "dev"
title: "incip"
---
<div class="elementSpec">
   <h3 id="incip">&lt;incip&gt;</h3>
   <table class="wovenodd">
      <tr>
         <td colspan="2" class="wovenodd-col2">(incipit) – The opening music and/or words of a composition.</td>
      </tr>
      <tr>
         <td class="wovenodd-col1"><strong>Module</strong></td>
         <td class="wovenodd-col2">MEI.shared</td>
      </tr>
      <tr>
         <td class="wovenodd-col1"><strong>Attributes</strong></td>
         <td class="wovenodd-col2">
            <table class="table table-striped">
               <thead>
                  <tr>
                     <th></th>
                  </tr>
               </thead>
               <tbody>
                  <tr>
                     <td>
                        <div class="attributeDef"><span class="attribute"><strong>@analog</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Contains a reference to a field or element in another descriptive encoding system
                              to
                              which this MEI element is comparable.</span>
                           Value is plain text.
                           <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.bibl.html">att.bibl</a></span></div>
                     </td>
                  </tr>
                  <tr>
                     <td>
                        <div class="attributeDef"><span class="attribute"><strong>@class</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Contains one or more URIs which denote classification terms that apply to the entity
                              bearing this attribute.</span>
                           One or more values from <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.uri.html">data.URI</a>, separated by spaces.
                           <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.classed.html">att.classed</a></span></div>
                     </td>
                  </tr>
                  <tr>
                     <td>
                        <div class="attributeDef"><span class="attribute"><strong>@copyof</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Points to an element of which the current element is a copy.</span>
                           Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.uri.html">data.URI</a>.
                           <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.linking.html">att.linking</a></span></div>
                     </td>
                  </tr>
                  <tr>
                     <td>
                        <div class="attributeDef"><span class="attribute"><strong>@corresp</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Used to point to other elements that correspond to this one in a generic
                              fashion.</span>
                           One or more values from <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.uri.html">data.URI</a>, separated by spaces.
                           <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.linking.html">att.linking</a></span></div>
                     </td>
                  </tr>
                  <tr>
                     <td>
                        <div class="attributeDef"><span class="attribute"><strong>@label</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Captures text to be used to generate a label for the element to which it's attached,
                              a
                              "tool tip" or prefatory text, for example. Should not be used to record document
                              content.</span>
                           Value is plain text.
                           <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.labelled.html">att.labelled</a></span></div>
                     </td>
                  </tr>
                  <tr>
                     <td>
                        <div class="attributeDef"><span class="attribute"><strong>@n</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Provides a number-like designation that indicates an element's position in a sequence
                              of similar elements. May not contain space characters.</span>
                           Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.word.html">data.WORD</a>.
                           <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.nnumberlike.html">att.nNumberLike</a></span></div>
                     </td>
                  </tr>
                  <tr>
                     <td>
                        <div class="attributeDef"><span class="attribute"><strong>@next</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Used to point to the next event(s) in a user-defined collection.</span>
                           One or more values from <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.uri.html">data.URI</a>, separated by spaces.
                           <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.linking.html">att.linking</a></span></div>
                     </td>
                  </tr>
                  <tr>
                     <td>
                        <div class="attributeDef"><span class="attribute"><strong>@prev</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Points to the previous event(s) in a user-defined collection.</span>
                           One or more values from <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.uri.html">data.URI</a>, separated by spaces.
                           <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.linking.html">att.linking</a></span></div>
                     </td>
                  </tr>
                  <tr>
                     <td>
                        <div class="attributeDef"><span class="attribute"><strong>@sameas</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Points to an element that is the same as the current element but is not a literal
                              copy
                              of the current element.</span>
                           One or more values from <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.uri.html">data.URI</a>, separated by spaces.
                           <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.linking.html">att.linking</a></span></div>
                     </td>
                  </tr>
                  <tr>
                     <td>
                        <div class="attributeDef"><span class="attribute"><strong>@synch</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Points to elements that are synchronous with the current element.</span>
                           One or more values from <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.uri.html">data.URI</a>, separated by spaces.
                           <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.linking.html">att.linking</a></span></div>
                     </td>
                  </tr>
                  <tr>
                     <td>
                        <div class="attributeDef"><span class="attribute"><strong>@type</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Designation which characterizes the element in some sense, using any convenient
                              classification scheme or typology that employs single-token labels.</span>
                           One or more values of datatype <span style="font-weight: 500;">NMTOKEN</span>, separated by spaces.
                           <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.typed.html">att.typed</a></span></div>
                     </td>
                  </tr>
                  <tr>
                     <td>
                        <div class="attributeDef"><span class="attribute"><strong>@xml:base</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Provides a base URI reference with which applications can resolve relative URI
                              references into absolute URI references.</span>
                           Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.uri.html">data.URI</a>.
                           <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.basic.html">att.basic</a></span></div>
                     </td>
                  </tr>
                  <tr>
                     <td>
                        <div class="attributeDef"><span class="attribute"><strong>@xml:id</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Regularizes the naming of an element and thus facilitates building links between it
                              and other resources. Each id attribute within a document must have a unique value.</span>
                           Value is a valid <a target="_blank" href="https://www.w3.org/TR/xml-id/">xml:id</a>.
                           <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.id.html">att.id</a></span></div>
                     </td>
                  </tr>
               </tbody>
            </table>
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1"><strong>Member of</strong></td>
         <td class="wovenodd-col2">
            <div class="parent"><a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/model-classes/model.inciplike.html">model.incipLike</a></div>
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1"><strong>Contained by</strong></td>
         <td class="wovenodd-col2">
            <div class="parent">
               <div class="specChildren">
                  <div class="specChild"><span class="specChildModule">MEI.frbr</span><span class="specChildElements"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/expression.html">expression</a></span></div>
                  <div class="specChild"><span class="specChildModule">MEI.header</span><span class="specChildElements"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/work.html">work</a></span></div>
               </div>
            </div>
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1"><strong>May contain</strong></td>
         <td class="wovenodd-col2">
            <div class="specChildren">
               <div class="specChild"><span class="specChildModule">MEI.figtable</span><span class="specChildElements"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/graphic.html">graphic</a></span></div>
               <div class="specChild"><span class="specChildModule">MEI.header</span><span class="specChildElements"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/incipcode.html">incipCode</a> <a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/inciptext.html">incipText</a> <a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/key.html">key</a> <a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/mensuration.html">mensuration</a> <a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/meter.html">meter</a> <a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/perfres.html">perfRes</a> <a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/perfreslist.html">perfResList</a></span></div>
               <div class="specChild"><span class="specChildModule">MEI.shared</span><span class="specChildElements"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/annot.html">annot</a> <a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/clef.html">clef</a> <a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/clefgrp.html">clefGrp</a> <a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/head.html">head</a> <a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/role.html">role</a> <a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/score.html">score</a> <a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/tempo.html">tempo</a></span></div>
            </div>
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1"><strong>Declaration</strong></td>
         <td class="wovenodd-col2">
            <div class="code" xml:space="preserve" data-lang="ODD"><code>
                  <div class="indent1 indent"><span data-indentation="1" class="element">&lt;classes&gt;</span>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;memberOf
                           <span class="attribute">key=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.common.html">att.common</a>"</span></span>/&gt;</span></div>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;memberOf
                           <span class="attribute">key=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.bibl.html">att.bibl</a>"</span></span>/&gt;</span></div>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;memberOf
                           <span class="attribute">key=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/model-classes/model.inciplike.html">model.incipLike</a>"</span></span>/&gt;</span></div>
                     <span data-indentation="1" class="element">&lt;/classes&gt;</span></div>
                  <div class="indent1 indent"><span data-indentation="1" class="element">&lt;content&gt;</span>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;zeroOrMore&gt;</span><div class="indent3 indent"><span data-indentation="3" class="element">&lt;ref
                              
                              <span class="attribute">name=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/model-classes/model.headlike.html">model.headLike</a>"</span></span>
                              /&gt;</span></div><span data-indentation="2" class="element">&lt;/zeroOrMore&gt;</span></div>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;optional&gt;</span><div class="indent3 indent"><span data-indentation="3" class="element">&lt;ref
                              
                              <span class="attribute">name=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/elements/tempo.html">tempo</a>"</span></span>
                              /&gt;</span></div><span data-indentation="2" class="element">&lt;/optional&gt;</span></div>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;optional&gt;</span><div class="indent3 indent"><span data-indentation="3" class="element">&lt;ref
                              
                              <span class="attribute">name=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/elements/role.html">role</a>"</span></span>
                              /&gt;</span></div><span data-indentation="2" class="element">&lt;/optional&gt;</span></div>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;optional&gt;</span><div class="indent3 indent"><span data-indentation="3" class="element">&lt;choice&gt;</span><div class="indent4 indent"><span data-indentation="4" class="element">&lt;ref
                                 
                                 <span class="attribute">name=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/elements/clef.html">clef</a>"</span></span>
                                 /&gt;</span></div>
                           <div class="indent4 indent"><span data-indentation="4" class="element">&lt;ref
                                 
                                 <span class="attribute">name=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/elements/clefgrp.html">clefGrp</a>"</span></span>
                                 /&gt;</span></div><span data-indentation="3" class="element">&lt;/choice&gt;</span></div><span data-indentation="2" class="element">&lt;/optional&gt;</span></div>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;optional&gt;</span><div class="indent3 indent"><span data-indentation="3" class="element">&lt;choice&gt;</span><div class="indent4 indent"><span data-indentation="4" class="element">&lt;ref
                                 
                                 <span class="attribute">name=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/elements/perfres.html">perfRes</a>"</span></span>
                                 /&gt;</span></div>
                           <div class="indent4 indent"><span data-indentation="4" class="element">&lt;ref
                                 
                                 <span class="attribute">name=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/elements/perfreslist.html">perfResList</a>"</span></span>
                                 /&gt;</span></div><span data-indentation="3" class="element">&lt;/choice&gt;</span></div><span data-indentation="2" class="element">&lt;/optional&gt;</span></div>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;optional&gt;</span><div class="indent3 indent"><span data-indentation="3" class="element">&lt;ref
                              
                              <span class="attribute">name=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/elements/key.html">key</a>"</span></span>
                              /&gt;</span></div><span data-indentation="2" class="element">&lt;/optional&gt;</span></div>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;optional&gt;</span><div class="indent3 indent"><span data-indentation="3" class="element">&lt;ref
                              
                              <span class="attribute">name=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/elements/meter.html">meter</a>"</span></span>
                              /&gt;</span></div><span data-indentation="2" class="element">&lt;/optional&gt;</span></div>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;optional&gt;</span><div class="indent3 indent"><span data-indentation="3" class="element">&lt;ref
                              
                              <span class="attribute">name=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/elements/mensuration.html">mensuration</a>"</span></span>
                              /&gt;</span></div><span data-indentation="2" class="element">&lt;/optional&gt;</span></div>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;zeroOrMore&gt;</span><div class="indent3 indent"><span data-indentation="3" class="element">&lt;choice&gt;</span><div class="indent4 indent"><span data-indentation="4" class="element">&lt;ref
                                 
                                 <span class="attribute">name=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/model-classes/model.annotlike.html">model.annotLike</a>"</span></span>
                                 /&gt;</span></div>
                           <div class="indent4 indent"><span data-indentation="4" class="element">&lt;ref
                                 
                                 <span class="attribute">name=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/model-classes/model.graphiclike.html">model.graphicLike</a>"</span></span>
                                 /&gt;</span></div>
                           <div class="indent4 indent"><span data-indentation="4" class="element">&lt;ref
                                 
                                 <span class="attribute">name=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/model-classes/model.scorelike.html">model.scoreLike</a>"</span></span>
                                 /&gt;</span></div>
                           <div class="indent4 indent"><span data-indentation="4" class="element">&lt;ref
                                 
                                 <span class="attribute">name=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/elements/incipcode.html">incipCode</a>"</span></span>
                                 /&gt;</span></div>
                           <div class="indent4 indent"><span data-indentation="4" class="element">&lt;ref
                                 
                                 <span class="attribute">name=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/elements/inciptext.html">incipText</a>"</span></span>
                                 /&gt;</span></div><span data-indentation="3" class="element">&lt;/choice&gt;</span></div><span data-indentation="2" class="element">&lt;/zeroOrMore&gt;</span></div>
                     <span data-indentation="1" class="element">&lt;/content&gt;</span></div></code></div>
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1"><strong>Remarks</strong></td>
         <td class="wovenodd-col2">
            <p>The <a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/incipText.html">incipText</a> element may be used to capture a text incipit, while
               <a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/score.html">score</a> is available to provide an MEI-encoded musical incipit. Images
               of an incipit may be referenced using the <a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/graphic.html">graphic</a> element. An incipit
               encoded in a text format other than MEI may be placed in the <a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/incipCode.html">incipCode</a>
               element.
            </p>
         </td>
      </tr>
   </table>
</div>