
<div class="header-banner purple">
<div class="header-label purple">DialogicTimeline</div>
</div>

*This contains the source code documentation of the class `DialogicTimeline`.*
        
# DialogicTimeline
**Inherits:** [Resource](https://docs.godotengine.org/en/latest/classes/class_resource.html#class-resource)

Resource that defines a list of events. It can store them as text and load them from text too.
## Properties
Name | Type | Default 
--- | --- | --- 
events | [Array](https://docs.godotengine.org/en/latest/classes/class_array.html#class-array) |   
events_processed | [bool](https://docs.godotengine.org/en/latest/classes/class_bool.html#class-bool) |  `false` 
--- 

## Methods
Returns | Method 
--- | --- 
<span class="hljs-attribute">[String](https://docs.godotengine.org/en/latest/classes/class_string.html#class-string)</span> | [<span class="hljs-title">as_text</span>](#property-as_text) ( ) 
<span style = "color: gray">void</span> | [<span class="hljs-title">clean</span>](#property-clean) ( ) 
<span style = "color: gray">void</span> | [<span class="hljs-title">from_text</span>](#property-from_text) ( `text`: [String](https://docs.godotengine.org/en/latest/classes/class_string.html#class-string) ) 
<span class="hljs-attribute">[Variant](https://docs.godotengine.org/en/latest/classes/class_variant.html#class-variant)</span> | [<span class="hljs-title">get_event</span>](#property-get_event) ( `index`: [int](https://docs.godotengine.org/en/latest/classes/class_int.html#class-int) ) 
<span style = "color: gray">void</span> | [<span class="hljs-title">process</span>](#property-process) ( ) 
--- 
## Property Descriptions



<a class="header" id="property-as_text" href="#property-as_text">**<span class="hljs-attribute">func</span> [<span class="hljs-title">as_text</span>](#property-as_text) ( )</a>  ⇒ <span class="hljs-attribute">[String](https://docs.godotengine.org/en/latest/classes/class_string.html#class-string)</span>** 



Stores all events in their text format and returns them as a string

---



<a class="header" id="property-clean" href="#property-clean">**<span class="hljs-attribute">func</span> [<span class="hljs-title">clean</span>](#property-clean) ( )</a>  ⇒ <span style = "color: gray">void</span>** 



This method makes sure that all events in a timeline are correctly reset

---



<a class="header" id="property-from_text" href="#property-from_text">**<span class="hljs-attribute">func</span> [<span class="hljs-title">from_text</span>](#property-from_text) ( `text`: [String](https://docs.godotengine.org/en/latest/classes/class_string.html#class-string) )</a>  ⇒ <span style = "color: gray">void</span>** 



Parses the lines as seperate events and insert them in an array, so they can be converted to DialogicEvent's when processed later

---



<a class="header" id="property-get_event" href="#property-get_event">**<span class="hljs-attribute">func</span> [<span class="hljs-title">get_event</span>](#property-get_event) ( `index`: [int](https://docs.godotengine.org/en/latest/classes/class_int.html#class-int) )</a>  ⇒ <span class="hljs-attribute">[Variant](https://docs.godotengine.org/en/latest/classes/class_variant.html#class-variant)</span>** 



Helper method

---



<a class="header" id="property-process" href="#property-process">**<span class="hljs-attribute">func</span> [<span class="hljs-title">process</span>](#property-process) ( )</a>  ⇒ <span style = "color: gray">void</span>** 



Method that loads all the event resources from the strings, if it wasn't done before

---

