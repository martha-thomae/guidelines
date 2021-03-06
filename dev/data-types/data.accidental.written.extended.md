---
layout: sidebar
sidebar: s1
version: "dev"
title: "data.ACCIDENTAL.WRITTEN.extended"
---
<div class="specPage">
   <div class="datatypeSpec">
      <h3 id="data.ACCIDENTAL.WRITTEN.extended">data.ACCIDENTAL.WRITTEN.extended</h3>
      <div class="specs">
         <div class="desc">Written quarter-tone accidental values.</div>
         <div class="facet module">
            <div class="label">Module</div>
            <div class="statement text">MEI</div>
         </div>
         <div class="facet usedBy" id="usedBy">
            <div class="label">Used by</div>
            <div class="statement list">
               <div class="classBox dtBox" title="Data Types">
                  <div class="classHeading"><label class="classLabel">Data Types</label><span class="classDesc">These other Data Types reference data.ACCIDENTAL.WRITTEN.extended</span></div>
                  <div class="classContent"><span class="ident datatype" data-ident="data.ACCIDENTAL.WRITTEN" data-module="MEI" title="Written accidental values."><a class="classLink" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.accidental.written.html">data.ACCIDENTAL.WRITTEN</a></span></div>
               </div>
            </div>
         </div>
         <div class="facet allowedValues" id="allowedValues">
            <div class="label">Allowed Values</div>
            <div class="statement list">
               <div class="dataValueBox" id="su"><span class="dataValue ident">su</span><span class="dataValue desc">Sharp note raised by quarter tone (sharp modified by arrow).</span></div>
               <div class="dataValueBox" id="sd"><span class="dataValue ident">sd</span><span class="dataValue desc">Sharp note lowered by quarter tone (sharp modified by arrow).</span></div>
               <div class="dataValueBox" id="fu"><span class="dataValue ident">fu</span><span class="dataValue desc">Flat note raised by quarter tone (flat modified by arrow).</span></div>
               <div class="dataValueBox" id="fd"><span class="dataValue ident">fd</span><span class="dataValue desc">Flat note lowered by quarter tone (flat modified by arrow).</span></div>
               <div class="dataValueBox" id="nu"><span class="dataValue ident">nu</span><span class="dataValue desc">Natural note raised by quarter tone (natural modified by arrow).</span></div>
               <div class="dataValueBox" id="nd"><span class="dataValue ident">nd</span><span class="dataValue desc">Natural note lowered by quarter tone (natural modified by arrow).</span></div>
               <div class="dataValueBox" id="1qf"><span class="dataValue ident">1qf</span><span class="dataValue desc">1/4-tone flat accidental.</span></div>
               <div class="dataValueBox" id="3qf"><span class="dataValue ident">3qf</span><span class="dataValue desc">3/4-tone flat accidental.</span></div>
               <div class="dataValueBox" id="1qs"><span class="dataValue ident">1qs</span><span class="dataValue desc">1/4-tone sharp accidental.</span></div>
               <div class="dataValueBox" id="3qs"><span class="dataValue ident">3qs</span><span class="dataValue desc">3/4-tone sharp accidental.</span></div>
            </div>
         </div>
         <div class="facet declaration">
            <div class="label">Declaration</div>
            <div class="statement declaration">
               <div class="code" xml:space="preserve" data-lang="ODD"><code>
                     <div class="indent1 indent"><span data-indentation="1" class="element">&lt;macroSpec <span class="attribute">ident=</span><span class="attributevalue">"data.ACCIDENTAL.WRITTEN.extended"</span> <span class="attribute">module=</span><span class="attributevalue">"MEI"</span> <span class="attribute">type=</span><span class="attributevalue">"dt"</span>&gt;</span>
                        
                        <div class="indent2 indent"><span data-indentation="2" class="element">&lt;desc&gt;</span>Written quarter-tone accidental values.<span data-indentation="2" class="element">&lt;/desc&gt;</span></div>
                        
                        <div class="indent2 indent"><span data-indentation="2" class="element">&lt;content&gt;</span>
                           
                           <div class="indent3 indent"><span data-indentation="3" class="element">&lt;valList <span class="attribute">type=</span><span class="attributevalue">"closed"</span>&gt;</span>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="comment">&lt;!-- su, sd, fu, fd are equivalent to usual symbols plus an arrow (Gould, p. 95)--&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"su"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;desc&gt;</span>Sharp note raised by quarter tone (sharp modified by arrow).<span data-indentation="5" class="element">&lt;/desc&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/valItem&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"sd"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;desc&gt;</span>Sharp note lowered by quarter tone (sharp modified by arrow).<span data-indentation="5" class="element">&lt;/desc&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/valItem&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"fu"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;desc&gt;</span>Flat note raised by quarter tone (flat modified by arrow).<span data-indentation="5" class="element">&lt;/desc&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/valItem&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"fd"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;desc&gt;</span>Flat note lowered by quarter tone (flat modified by arrow).<span data-indentation="5" class="element">&lt;/desc&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/valItem&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"nu"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;desc&gt;</span>Natural note raised by quarter tone (natural modified by arrow).<span data-indentation="5" class="element">&lt;/desc&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/valItem&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"nd"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;desc&gt;</span>Natural note lowered by quarter tone (natural modified by arrow).<span data-indentation="5" class="element">&lt;/desc&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/valItem&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="comment">&lt;!-- 1qf, 3qf, 1qs, 3qs represent fixed symbols (Gould, p. 96) --&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"1qf"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;desc&gt;</span>1/4-tone flat accidental.<span data-indentation="5" class="element">&lt;/desc&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/valItem&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"3qf"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;desc&gt;</span>3/4-tone flat accidental.<span data-indentation="5" class="element">&lt;/desc&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/valItem&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"1qs"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;desc&gt;</span>1/4-tone sharp accidental.<span data-indentation="5" class="element">&lt;/desc&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/valItem&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;valItem <span class="attribute">ident=</span><span class="attributevalue">"3qs"</span>&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;desc&gt;</span>3/4-tone sharp accidental.<span data-indentation="5" class="element">&lt;/desc&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/valItem&gt;</span></div>
                              <span data-indentation="3" class="element">&lt;/valList&gt;</span></div>
                           <span data-indentation="2" class="element">&lt;/content&gt;</span></div>
                        <span data-indentation="1" class="element">&lt;/macroSpec&gt;</span></div></code></div>
            </div>
         </div>
      </div><script type="text/javascript">
            
            var tabbedFacets = document.querySelectorAll('.facet ul.tab');
            
            var tabClick = function(e) {
                var style = e.target.getAttribute('data-display');
                var facetId = e.target.parentNode.parentNode.parentNode.parentNode.id;
                setTabs(facetId,style)
            }
            
            for(var facetUl of tabbedFacets) {
                var facetElem = facetUl.parentNode.parentNode;
                var facetId = facetElem.id;
                var storageName = 'meiSpecs_' + facetId + '_display';
                var defaultValue = facetUl.children[0].children[0].getAttribute('data-display');
                
                if(localStorage.getItem(storageName) === null) {
                    setTabs(facetElem.id,defaultValue);
                } else {
                    setTabs(facetElem.id,localStorage.getItem(storageName));
                }
                
                var tabs = facetUl.querySelectorAll('.tab-item a');
                
                for(var tab of tabs) {
                    tab.addEventListener('click',tabClick);
                }
                
            }
            
            function setTabs(facetId,style) {
                
                var storageName = 'meiSpecs_' + facetId + '_display';
                localStorage.setItem(storageName,style);
                
                var facetElem = document.getElementById(facetId);
                
                var oldTab = facetElem.querySelector('.displayTab.active');
                oldTab.classList.remove('active');
                
                var newTab = document.getElementById(facetId + '_' + style + '_tab');
                newTab.classList.add('active');
                
                var oldBox = facetElem.querySelector('.active.facetTabbedContent');
                oldBox.classList.remove('active');
                oldBox.style.display = 'none';
                
                var newBox = document.getElementById(facetId + '_tabbedContent_' + style);
                newBox.classList.add('active');
                newBox.style.display = 'block';
                
            }
        </script></div>
</div>