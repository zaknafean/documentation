
<div class="header-banner purple">
<div class="header-label purple">DialogicConditionEvent</div>
</div>

*This contains the source code documentation of the class `DialogicConditionEvent`.*
        
# DialogicConditionEvent
**Inherits:** [DialogicEvent](class_dialogicevent.md)

Event that allows branching a timeline based on a condition.
## Properties
Name | Type | Default 
--- | --- | --- 
condition | [String](https://docs.godotengine.org/en/latest/classes/class_string.html#class-string) |  `""` 
condition_type | [int](https://docs.godotengine.org/en/latest/classes/class_int.html#class-int) |  `0` 
--- 

## Methods
Returns | Method 
--- | --- 
<span style = "color: gray">void</span> | [<span class="hljs-title">build_event_editor</span>](#property-build_event_editor) ( ) 
<span style = "color: gray">void</span> | [<span class="hljs-title">from_text</span>](#property-from_text) ( `string`: [String](https://docs.godotengine.org/en/latest/classes/class_string.html#class-string) ) 
<span class="hljs-attribute">[Control](https://docs.godotengine.org/en/latest/classes/class_control.html#class-control)</span> | [<span class="hljs-title">get_end_branch_control</span>](#property-get_end_branch_control) ( ) 
<span class="hljs-attribute">[bool](https://docs.godotengine.org/en/latest/classes/class_bool.html#class-bool)</span> | [<span class="hljs-title">is_valid_event</span>](#property-is_valid_event) ( `string`: [String](https://docs.godotengine.org/en/latest/classes/class_string.html#class-string) ) 
<span class="hljs-attribute">[bool](https://docs.godotengine.org/en/latest/classes/class_bool.html#class-bool)</span> | [<span class="hljs-title">should_execute_this_branch</span>](#property-should_execute_this_branch) ( ) 
<span class="hljs-attribute">[String](https://docs.godotengine.org/en/latest/classes/class_string.html#class-string)</span> | [<span class="hljs-title">to_text</span>](#property-to_text) ( ) 
--- 
## Constants


<a class="header" id="constant-IF" href="#constant-IF">**<span class="hljs-attribute">const</span> <span class="hljs-title">IF</span><span class="hljs-comment"> = 0</span>**</a>



 <span style = "color: gray">*No description available.*</span> 

---


<a class="header" id="constant-ELIF" href="#constant-ELIF">**<span class="hljs-attribute">const</span> <span class="hljs-title">ELIF</span><span class="hljs-comment"> = 1</span>**</a>



 <span style = "color: gray">*No description available.*</span> 

---


<a class="header" id="constant-ELSE" href="#constant-ELSE">**<span class="hljs-attribute">const</span> <span class="hljs-title">ELSE</span><span class="hljs-comment"> = 2</span>**</a>



 <span style = "color: gray">*No description available.*</span> 

---
## Property Descriptions



<a class="header" id="property-build_event_editor" href="#property-build_event_editor">**<span class="hljs-attribute">func</span> [<span class="hljs-title">build_event_editor</span>](#property-build_event_editor) ( )</a>  ⇒ <span style = "color: gray">void</span>** 



 <span style = "color: gray">*No description available.*</span> 

---



<a class="header" id="property-from_text" href="#property-from_text">**<span class="hljs-attribute">func</span> [<span class="hljs-title">from_text</span>](#property-from_text) ( `string`: [String](https://docs.godotengine.org/en/latest/classes/class_string.html#class-string) )</a>  ⇒ <span style = "color: gray">void</span>** 



 <span style = "color: gray">*No description available.*</span> 

---



<a class="header" id="property-get_end_branch_control" href="#property-get_end_branch_control">**<span class="hljs-attribute">func</span> [<span class="hljs-title">get_end_branch_control</span>](#property-get_end_branch_control) ( )</a>  ⇒ <span class="hljs-attribute">[Control](https://docs.godotengine.org/en/latest/classes/class_control.html#class-control)</span>** 



 <span style = "color: gray">*No description available.*</span> 

---



<a class="header" id="property-is_valid_event" href="#property-is_valid_event">**<span class="hljs-attribute">func</span> [<span class="hljs-title">is_valid_event</span>](#property-is_valid_event) ( `string`: [String](https://docs.godotengine.org/en/latest/classes/class_string.html#class-string) )</a>  ⇒ <span class="hljs-attribute">[bool](https://docs.godotengine.org/en/latest/classes/class_bool.html#class-bool)</span>** 



 <span style = "color: gray">*No description available.*</span> 

---



<a class="header" id="property-should_execute_this_branch" href="#property-should_execute_this_branch">**<span class="hljs-attribute">func</span> [<span class="hljs-title">should_execute_this_branch</span>](#property-should_execute_this_branch) ( )</a>  ⇒ <span class="hljs-attribute">[bool](https://docs.godotengine.org/en/latest/classes/class_bool.html#class-bool)</span>** 



only called if the previous event was an end-branch event return true if this event should be executed if the previous event was an end-branch event

---



<a class="header" id="property-to_text" href="#property-to_text">**<span class="hljs-attribute">func</span> [<span class="hljs-title">to_text</span>](#property-to_text) ( )</a>  ⇒ <span class="hljs-attribute">[String](https://docs.godotengine.org/en/latest/classes/class_string.html#class-string)</span>** 



 <span style = "color: gray">*No description available.*</span> 

---

