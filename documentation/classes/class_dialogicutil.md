
<div class="header-banner purple">
<div class="header-label purple">DialogicUtil</div>
</div>

*This contains the source code documentation of the class `DialogicUtil`.*
        
# DialogicUtil
**Inherits:** [RefCounted](https://docs.godotengine.org/en/latest/classes/class_refcounted.html#class-refcounted)

Script that container helper methods for both editor and game execution. Used whenever the same thing is needed in different parts of the plugin.
--- 

## Methods
Returns | Method 
--- | --- 
<span style = "color: gray">void</span> | [<span class="hljs-title">apply_scene_export_overrides</span>](#property-apply_scene_export_overrides) ( `node`: [Node](https://docs.godotengine.org/en/latest/classes/class_node.html#class-node), `export_overrides`: [Dictionary](https://docs.godotengine.org/en/latest/classes/class_dictionary.html#class-dictionary), `apply`: [bool](https://docs.godotengine.org/en/latest/classes/class_bool.html#class-bool) = `true` ) 
<span class="hljs-attribute">[DialogicGameHandler](class_dialogicgamehandler.md)</span> | [<span class="hljs-title">autoload</span>](#property-autoload) ( ) 
<span class="hljs-attribute">[Color](https://docs.godotengine.org/en/latest/classes/class_color.html#class-color)</span> | [<span class="hljs-title">get_color</span>](#property-get_color) ( `value`: [String](https://docs.godotengine.org/en/latest/classes/class_string.html#class-string) ) 
<span class="hljs-attribute">[Dictionary](https://docs.godotengine.org/en/latest/classes/class_dictionary.html#class-dictionary)</span> | [<span class="hljs-title">get_color_palette</span>](#property-get_color_palette) ( `default`: [bool](https://docs.godotengine.org/en/latest/classes/class_bool.html#class-bool) = `false` ) 
<span class="hljs-attribute">[Dictionary](https://docs.godotengine.org/en/latest/classes/class_dictionary.html#class-dictionary)</span> | [<span class="hljs-title">get_custom_event_defaults</span>](#property-get_custom_event_defaults) ( `event_name`: [String](https://docs.godotengine.org/en/latest/classes/class_string.html#class-string) ) 
<span class="hljs-attribute">[PackedScene](https://docs.godotengine.org/en/latest/classes/class_packedscene.html#class-packedscene)</span> | [<span class="hljs-title">get_default_layout_base</span>](#property-get_default_layout_base) ( ) 
<span class="hljs-attribute">[DialogicStyle](class_dialogicstyle.md)</span> | [<span class="hljs-title">get_default_style</span>](#property-get_default_style) ( ) 
<span class="hljs-attribute">[Dictionary](https://docs.godotengine.org/en/latest/classes/class_dictionary.html#class-dictionary)</span> | [<span class="hljs-title">get_default_variables</span>](#property-get_default_variables) ( ) 
<span class="hljs-attribute">[Node](https://docs.godotengine.org/en/latest/classes/class_node.html#class-node)</span> | [<span class="hljs-title">get_dialogic_plugin</span>](#property-get_dialogic_plugin) ( ) 
<span class="hljs-attribute">[float](https://docs.godotengine.org/en/latest/classes/class_float.html#class-float)</span> | [<span class="hljs-title">get_editor_scale</span>](#property-get_editor_scale) ( ) 
<span class="hljs-attribute">[Variant](https://docs.godotengine.org/en/latest/classes/class_variant.html#class-variant)</span> | [<span class="hljs-title">get_editor_setting</span>](#property-get_editor_setting) ( `setting`: [String](https://docs.godotengine.org/en/latest/classes/class_string.html#class-string), `default`: [Variant](https://docs.godotengine.org/en/latest/classes/class_variant.html#class-variant) = `null` ) 
<span class="hljs-attribute">[DialogicStyle](class_dialogicstyle.md)</span> | [<span class="hljs-title">get_fallback_style</span>](#property-get_fallback_style) ( ) 
<span class="hljs-attribute">[DialogicIndexer[]](https://docs.godotengine.org/en/latest/classes/class_dialogicindexer.html#class-dialogicindexer)</span> | [<span class="hljs-title">get_indexers</span>](#property-get_indexers) ( `include_custom`: [bool](https://docs.godotengine.org/en/latest/classes/class_bool.html#class-bool) = `true`, `force_reload`: [bool](https://docs.godotengine.org/en/latest/classes/class_bool.html#class-bool) = `false` ) 
<span class="hljs-attribute">[String](https://docs.godotengine.org/en/latest/classes/class_string.html#class-string)</span> | [<span class="hljs-title">get_module_path</span>](#property-get_module_path) ( `name`: [String](https://docs.godotengine.org/en/latest/classes/class_string.html#class-string), `builtin`: [bool](https://docs.godotengine.org/en/latest/classes/class_bool.html#class-bool) = `true` ) 
<span class="hljs-attribute">[String](https://docs.godotengine.org/en/latest/classes/class_string.html#class-string)</span> | [<span class="hljs-title">get_next_translation_id</span>](#property-get_next_translation_id) ( ) 
<span class="hljs-attribute">[Array](https://docs.godotengine.org/en/latest/classes/class_array.html#class-array)</span> | [<span class="hljs-title">get_portrait_animation_scripts</span>](#property-get_portrait_animation_scripts) ( `type`: [int](https://docs.godotengine.org/en/latest/classes/class_int.html#class-int) = `0`, `include_custom`: [bool](https://docs.godotengine.org/en/latest/classes/class_bool.html#class-bool) = `true` ) 
<span class="hljs-attribute">[Dictionary](https://docs.godotengine.org/en/latest/classes/class_dictionary.html#class-dictionary)</span> | [<span class="hljs-title">get_scene_export_defaults</span>](#property-get_scene_export_defaults) ( `node`: [Node](https://docs.godotengine.org/en/latest/classes/class_node.html#class-node) ) 
<span class="hljs-attribute">[DialogicStyle](class_dialogicstyle.md)</span> | [<span class="hljs-title">get_style_by_name</span>](#property-get_style_by_name) ( `name`: [String](https://docs.godotengine.org/en/latest/classes/class_string.html#class-string) ) 
<span class="hljs-attribute">[int](https://docs.godotengine.org/en/latest/classes/class_int.html#class-int)</span> | [<span class="hljs-title">get_variable_type</span>](#property-get_variable_type) ( `path`: [String](https://docs.godotengine.org/en/latest/classes/class_string.html#class-string), `dict`: [Dictionary](https://docs.godotengine.org/en/latest/classes/class_dictionary.html#class-dictionary) = `<unknown>` ) 
<span class="hljs-attribute">[int](https://docs.godotengine.org/en/latest/classes/class_int.html#class-int)</span> | [<span class="hljs-title">get_variable_value_type</span>](#property-get_variable_value_type) ( `value`: [Variant](https://docs.godotengine.org/en/latest/classes/class_variant.html#class-variant) ) 
<span class="hljs-attribute">[bool](https://docs.godotengine.org/en/latest/classes/class_bool.html#class-bool)</span> | [<span class="hljs-title">is_physics_timer</span>](#property-is_physics_timer) ( ) 
<span class="hljs-attribute">[Array](https://docs.godotengine.org/en/latest/classes/class_array.html#class-array)</span> | [<span class="hljs-title">list_variables</span>](#property-list_variables) ( `dict`: [Dictionary](https://docs.godotengine.org/en/latest/classes/class_dictionary.html#class-dictionary), `path`: [String](https://docs.godotengine.org/en/latest/classes/class_string.html#class-string) = `""`, `type`: [int](https://docs.godotengine.org/en/latest/classes/class_int.html#class-int) = `0` ) 
<span class="hljs-attribute">[Array](https://docs.godotengine.org/en/latest/classes/class_array.html#class-array)</span> | [<span class="hljs-title">listdir</span>](#property-listdir) ( `path`: [String](https://docs.godotengine.org/en/latest/classes/class_string.html#class-string), `files_only`: [bool](https://docs.godotengine.org/en/latest/classes/class_bool.html#class-bool) = `true`, `throw_error`: [bool](https://docs.godotengine.org/en/latest/classes/class_bool.html#class-bool) = `true`, `full_file_path`: [bool](https://docs.godotengine.org/en/latest/classes/class_bool.html#class-bool) = `false`, `include_imports`: [bool](https://docs.godotengine.org/en/latest/classes/class_bool.html#class-bool) = `false` ) 
<span class="hljs-attribute">[Variant](https://docs.godotengine.org/en/latest/classes/class_variant.html#class-variant)</span> | [<span class="hljs-title">logical_convert</span>](#property-logical_convert) ( `value`: [Variant](https://docs.godotengine.org/en/latest/classes/class_variant.html#class-variant) ) 
<span class="hljs-attribute">[String](https://docs.godotengine.org/en/latest/classes/class_string.html#class-string)</span> | [<span class="hljs-title">pretty_name</span>](#property-pretty_name) ( `script`: [String](https://docs.godotengine.org/en/latest/classes/class_string.html#class-string) ) 
<span style = "color: gray">void</span> | [<span class="hljs-title">set_editor_setting</span>](#property-set_editor_setting) ( `setting`: [String](https://docs.godotengine.org/en/latest/classes/class_string.html#class-string), `value`: [Variant](https://docs.godotengine.org/en/latest/classes/class_variant.html#class-variant) ) 
<span class="hljs-attribute">[Control](https://docs.godotengine.org/en/latest/classes/class_control.html#class-control)</span> | [<span class="hljs-title">setup_script_property_edit_node</span>](#property-setup_script_property_edit_node) ( `property_info`: [Dictionary](https://docs.godotengine.org/en/latest/classes/class_dictionary.html#class-dictionary), `value`: [Variant](https://docs.godotengine.org/en/latest/classes/class_variant.html#class-variant), `property_changed`: [Callable](https://docs.godotengine.org/en/latest/classes/class_callable.html#class-callable) ) 
<span class="hljs-attribute">[bool](https://docs.godotengine.org/en/latest/classes/class_bool.html#class-bool)</span> | [<span class="hljs-title">str_to_bool</span>](#property-str_to_bool) ( `boolstring`: [String](https://docs.godotengine.org/en/latest/classes/class_string.html#class-string) ) 
<span class="hljs-attribute">[Dictionary](https://docs.godotengine.org/en/latest/classes/class_dictionary.html#class-dictionary)</span> | [<span class="hljs-title">str_to_hash_set</span>](#property-str_to_hash_set) ( `source`: [String](https://docs.godotengine.org/en/latest/classes/class_string.html#class-string) ) 
<span style = "color: gray">void</span> | [<span class="hljs-title">update_autoload_subsystem_access</span>](#property-update_autoload_subsystem_access) ( ) 
<span style = "color: gray">void</span> | [<span class="hljs-title">update_timer_process_callback</span>](#property-update_timer_process_callback) ( `timer`: [Timer](https://docs.godotengine.org/en/latest/classes/class_timer.html#class-timer) ) 
--- 
## Constants


<a class="header" id="constant-ALL" href="#constant-ALL">**<span class="hljs-attribute">const</span> <span class="hljs-title">ALL</span><span class="hljs-comment"> = 0</span>**</a>



 <span style = "color: gray">*No description available.*</span> 

---


<a class="header" id="constant-IN" href="#constant-IN">**<span class="hljs-attribute">const</span> <span class="hljs-title">IN</span><span class="hljs-comment"> = 1</span>**</a>



 <span style = "color: gray">*No description available.*</span> 

---


<a class="header" id="constant-OUT" href="#constant-OUT">**<span class="hljs-attribute">const</span> <span class="hljs-title">OUT</span><span class="hljs-comment"> = 2</span>**</a>



 <span style = "color: gray">*No description available.*</span> 

---


<a class="header" id="constant-ACTION" href="#constant-ACTION">**<span class="hljs-attribute">const</span> <span class="hljs-title">ACTION</span><span class="hljs-comment"> = 3</span>**</a>



 <span style = "color: gray">*No description available.*</span> 

---


<a class="header" id="constant-ANY" href="#constant-ANY">**<span class="hljs-attribute">const</span> <span class="hljs-title">ANY</span><span class="hljs-comment"> = 0</span>**</a>



 <span style = "color: gray">*No description available.*</span> 

---


<a class="header" id="constant-STRING" href="#constant-STRING">**<span class="hljs-attribute">const</span> <span class="hljs-title">STRING</span><span class="hljs-comment"> = 1</span>**</a>



 <span style = "color: gray">*No description available.*</span> 

---


<a class="header" id="constant-FLOAT" href="#constant-FLOAT">**<span class="hljs-attribute">const</span> <span class="hljs-title">FLOAT</span><span class="hljs-comment"> = 2</span>**</a>



 <span style = "color: gray">*No description available.*</span> 

---


<a class="header" id="constant-INT" href="#constant-INT">**<span class="hljs-attribute">const</span> <span class="hljs-title">INT</span><span class="hljs-comment"> = 3</span>**</a>



 <span style = "color: gray">*No description available.*</span> 

---


<a class="header" id="constant-BOOL" href="#constant-BOOL">**<span class="hljs-attribute">const</span> <span class="hljs-title">BOOL</span><span class="hljs-comment"> = 4</span>**</a>



 <span style = "color: gray">*No description available.*</span> 

---
## Property Descriptions



<a class="header" id="property-apply_scene_export_overrides" href="#property-apply_scene_export_overrides">**<span class="hljs-attribute">func</span> [<span class="hljs-title">apply_scene_export_overrides</span>](#property-apply_scene_export_overrides) ( `node`: [Node](https://docs.godotengine.org/en/latest/classes/class_node.html#class-node), `export_overrides`: [Dictionary](https://docs.godotengine.org/en/latest/classes/class_dictionary.html#class-dictionary), `apply`: [bool](https://docs.godotengine.org/en/latest/classes/class_bool.html#class-bool) = `true` )</a>  ⇒ <span style = "color: gray">void</span>** 



 <span style = "color: gray">*No description available.*</span> 

---



<a class="header" id="property-autoload" href="#property-autoload">**<span class="hljs-attribute">func</span> [<span class="hljs-title">autoload</span>](#property-autoload) ( )</a>  ⇒ <span class="hljs-attribute">[DialogicGameHandler](class_dialogicgamehandler.md)</span>** 



Returns the autoload when in-game.

---



<a class="header" id="property-get_color" href="#property-get_color">**<span class="hljs-attribute">func</span> [<span class="hljs-title">get_color</span>](#property-get_color) ( `value`: [String](https://docs.godotengine.org/en/latest/classes/class_string.html#class-string) )</a>  ⇒ <span class="hljs-attribute">[Color](https://docs.godotengine.org/en/latest/classes/class_color.html#class-color)</span>** 



 <span style = "color: gray">*No description available.*</span> 

---



<a class="header" id="property-get_color_palette" href="#property-get_color_palette">**<span class="hljs-attribute">func</span> [<span class="hljs-title">get_color_palette</span>](#property-get_color_palette) ( `default`: [bool](https://docs.godotengine.org/en/latest/classes/class_bool.html#class-bool) = `false` )</a>  ⇒ <span class="hljs-attribute">[Dictionary](https://docs.godotengine.org/en/latest/classes/class_dictionary.html#class-dictionary)</span>** 



 <span style = "color: gray">*No description available.*</span> 

---



<a class="header" id="property-get_custom_event_defaults" href="#property-get_custom_event_defaults">**<span class="hljs-attribute">func</span> [<span class="hljs-title">get_custom_event_defaults</span>](#property-get_custom_event_defaults) ( `event_name`: [String](https://docs.godotengine.org/en/latest/classes/class_string.html#class-string) )</a>  ⇒ <span class="hljs-attribute">[Dictionary](https://docs.godotengine.org/en/latest/classes/class_dictionary.html#class-dictionary)</span>** 



 <span style = "color: gray">*No description available.*</span> 

---



<a class="header" id="property-get_default_layout_base" href="#property-get_default_layout_base">**<span class="hljs-attribute">func</span> [<span class="hljs-title">get_default_layout_base</span>](#property-get_default_layout_base) ( )</a>  ⇒ <span class="hljs-attribute">[PackedScene](https://docs.godotengine.org/en/latest/classes/class_packedscene.html#class-packedscene)</span>** 



 <span style = "color: gray">*No description available.*</span> 

---



<a class="header" id="property-get_default_style" href="#property-get_default_style">**<span class="hljs-attribute">func</span> [<span class="hljs-title">get_default_style</span>](#property-get_default_style) ( )</a>  ⇒ <span class="hljs-attribute">[DialogicStyle](class_dialogicstyle.md)</span>** 



 <span style = "color: gray">*No description available.*</span> 

---



<a class="header" id="property-get_default_variables" href="#property-get_default_variables">**<span class="hljs-attribute">func</span> [<span class="hljs-title">get_default_variables</span>](#property-get_default_variables) ( )</a>  ⇒ <span class="hljs-attribute">[Dictionary](https://docs.godotengine.org/en/latest/classes/class_dictionary.html#class-dictionary)</span>** 



 <span style = "color: gray">*No description available.*</span> 

---



<a class="header" id="property-get_dialogic_plugin" href="#property-get_dialogic_plugin">**<span class="hljs-attribute">func</span> [<span class="hljs-title">get_dialogic_plugin</span>](#property-get_dialogic_plugin) ( )</a>  ⇒ <span class="hljs-attribute">[Node](https://docs.godotengine.org/en/latest/classes/class_node.html#class-node)</span>** 



Although this does in fact always return a EditorPlugin node, that class is apparently not present in export and referencing it here creates a crash.

---



<a class="header" id="property-get_editor_scale" href="#property-get_editor_scale">**<span class="hljs-attribute">func</span> [<span class="hljs-title">get_editor_scale</span>](#property-get_editor_scale) ( )</a>  ⇒ <span class="hljs-attribute">[float](https://docs.godotengine.org/en/latest/classes/class_float.html#class-float)</span>** 



##############################################################################

---



<a class="header" id="property-get_editor_setting" href="#property-get_editor_setting">**<span class="hljs-attribute">func</span> [<span class="hljs-title">get_editor_setting</span>](#property-get_editor_setting) ( `setting`: [String](https://docs.godotengine.org/en/latest/classes/class_string.html#class-string), `default`: [Variant](https://docs.godotengine.org/en/latest/classes/class_variant.html#class-variant) = `null` )</a>  ⇒ <span class="hljs-attribute">[Variant](https://docs.godotengine.org/en/latest/classes/class_variant.html#class-variant)</span>** 



 <span style = "color: gray">*No description available.*</span> 

---



<a class="header" id="property-get_fallback_style" href="#property-get_fallback_style">**<span class="hljs-attribute">func</span> [<span class="hljs-title">get_fallback_style</span>](#property-get_fallback_style) ( )</a>  ⇒ <span class="hljs-attribute">[DialogicStyle](class_dialogicstyle.md)</span>** 



 <span style = "color: gray">*No description available.*</span> 

---



<a class="header" id="property-get_indexers" href="#property-get_indexers">**<span class="hljs-attribute">func</span> [<span class="hljs-title">get_indexers</span>](#property-get_indexers) ( `include_custom`: [bool](https://docs.godotengine.org/en/latest/classes/class_bool.html#class-bool) = `true`, `force_reload`: [bool](https://docs.godotengine.org/en/latest/classes/class_bool.html#class-bool) = `false` )</a>  ⇒ <span class="hljs-attribute">[DialogicIndexer[]](https://docs.godotengine.org/en/latest/classes/class_dialogicindexer.html#class-dialogicindexer)</span>** 



 <span style = "color: gray">*No description available.*</span> 

---



<a class="header" id="property-get_module_path" href="#property-get_module_path">**<span class="hljs-attribute">func</span> [<span class="hljs-title">get_module_path</span>](#property-get_module_path) ( `name`: [String](https://docs.godotengine.org/en/latest/classes/class_string.html#class-string), `builtin`: [bool](https://docs.godotengine.org/en/latest/classes/class_bool.html#class-bool) = `true` )</a>  ⇒ <span class="hljs-attribute">[String](https://docs.godotengine.org/en/latest/classes/class_string.html#class-string)</span>** 



 <span style = "color: gray">*No description available.*</span> 

---



<a class="header" id="property-get_next_translation_id" href="#property-get_next_translation_id">**<span class="hljs-attribute">func</span> [<span class="hljs-title">get_next_translation_id</span>](#property-get_next_translation_id) ( )</a>  ⇒ <span class="hljs-attribute">[String](https://docs.godotengine.org/en/latest/classes/class_string.html#class-string)</span>** 



 <span style = "color: gray">*No description available.*</span> 

---



<a class="header" id="property-get_portrait_animation_scripts" href="#property-get_portrait_animation_scripts">**<span class="hljs-attribute">func</span> [<span class="hljs-title">get_portrait_animation_scripts</span>](#property-get_portrait_animation_scripts) ( `type`: [int](https://docs.godotengine.org/en/latest/classes/class_int.html#class-int) = `0`, `include_custom`: [bool](https://docs.godotengine.org/en/latest/classes/class_bool.html#class-bool) = `true` )</a>  ⇒ <span class="hljs-attribute">[Array](https://docs.godotengine.org/en/latest/classes/class_array.html#class-array)</span>** 



 <span style = "color: gray">*No description available.*</span> 

---



<a class="header" id="property-get_scene_export_defaults" href="#property-get_scene_export_defaults">**<span class="hljs-attribute">func</span> [<span class="hljs-title">get_scene_export_defaults</span>](#property-get_scene_export_defaults) ( `node`: [Node](https://docs.godotengine.org/en/latest/classes/class_node.html#class-node) )</a>  ⇒ <span class="hljs-attribute">[Dictionary](https://docs.godotengine.org/en/latest/classes/class_dictionary.html#class-dictionary)</span>** 



 <span style = "color: gray">*No description available.*</span> 

---



<a class="header" id="property-get_style_by_name" href="#property-get_style_by_name">**<span class="hljs-attribute">func</span> [<span class="hljs-title">get_style_by_name</span>](#property-get_style_by_name) ( `name`: [String](https://docs.godotengine.org/en/latest/classes/class_string.html#class-string) )</a>  ⇒ <span class="hljs-attribute">[DialogicStyle](class_dialogicstyle.md)</span>** 



 <span style = "color: gray">*No description available.*</span> 

---



<a class="header" id="property-get_variable_type" href="#property-get_variable_type">**<span class="hljs-attribute">func</span> [<span class="hljs-title">get_variable_type</span>](#property-get_variable_type) ( `path`: [String](https://docs.godotengine.org/en/latest/classes/class_string.html#class-string), `dict`: [Dictionary](https://docs.godotengine.org/en/latest/classes/class_dictionary.html#class-dictionary) = `<unknown>` )</a>  ⇒ <span class="hljs-attribute">[int](https://docs.godotengine.org/en/latest/classes/class_int.html#class-int)</span>** 



 <span style = "color: gray">*No description available.*</span> 

---



<a class="header" id="property-get_variable_value_type" href="#property-get_variable_value_type">**<span class="hljs-attribute">func</span> [<span class="hljs-title">get_variable_value_type</span>](#property-get_variable_value_type) ( `value`: [Variant](https://docs.godotengine.org/en/latest/classes/class_variant.html#class-variant) )</a>  ⇒ <span class="hljs-attribute">[int](https://docs.godotengine.org/en/latest/classes/class_int.html#class-int)</span>** 



 <span style = "color: gray">*No description available.*</span> 

---



<a class="header" id="property-is_physics_timer" href="#property-is_physics_timer">**<span class="hljs-attribute">func</span> [<span class="hljs-title">is_physics_timer</span>](#property-is_physics_timer) ( )</a>  ⇒ <span class="hljs-attribute">[bool](https://docs.godotengine.org/en/latest/classes/class_bool.html#class-bool)</span>** 



##############################################################################

---



<a class="header" id="property-list_variables" href="#property-list_variables">**<span class="hljs-attribute">func</span> [<span class="hljs-title">list_variables</span>](#property-list_variables) ( `dict`: [Dictionary](https://docs.godotengine.org/en/latest/classes/class_dictionary.html#class-dictionary), `path`: [String](https://docs.godotengine.org/en/latest/classes/class_string.html#class-string) = `""`, `type`: [int](https://docs.godotengine.org/en/latest/classes/class_int.html#class-int) = `0` )</a>  ⇒ <span class="hljs-attribute">[Array](https://docs.godotengine.org/en/latest/classes/class_array.html#class-array)</span>** 



 <span style = "color: gray">*No description available.*</span> 

---



<a class="header" id="property-listdir" href="#property-listdir">**<span class="hljs-attribute">func</span> [<span class="hljs-title">listdir</span>](#property-listdir) ( `path`: [String](https://docs.godotengine.org/en/latest/classes/class_string.html#class-string), `files_only`: [bool](https://docs.godotengine.org/en/latest/classes/class_bool.html#class-bool) = `true`, `throw_error`: [bool](https://docs.godotengine.org/en/latest/classes/class_bool.html#class-bool) = `true`, `full_file_path`: [bool](https://docs.godotengine.org/en/latest/classes/class_bool.html#class-bool) = `false`, `include_imports`: [bool](https://docs.godotengine.org/en/latest/classes/class_bool.html#class-bool) = `false` )</a>  ⇒ <span class="hljs-attribute">[Array](https://docs.godotengine.org/en/latest/classes/class_array.html#class-array)</span>** 



##############################################################################

---



<a class="header" id="property-logical_convert" href="#property-logical_convert">**<span class="hljs-attribute">func</span> [<span class="hljs-title">logical_convert</span>](#property-logical_convert) ( `value`: [Variant](https://docs.godotengine.org/en/latest/classes/class_variant.html#class-variant) )</a>  ⇒ <span class="hljs-attribute">[Variant](https://docs.godotengine.org/en/latest/classes/class_variant.html#class-variant)</span>** 



 <span style = "color: gray">*No description available.*</span> 

---



<a class="header" id="property-pretty_name" href="#property-pretty_name">**<span class="hljs-attribute">func</span> [<span class="hljs-title">pretty_name</span>](#property-pretty_name) ( `script`: [String](https://docs.godotengine.org/en/latest/classes/class_string.html#class-string) )</a>  ⇒ <span class="hljs-attribute">[String](https://docs.godotengine.org/en/latest/classes/class_string.html#class-string)</span>** 



 <span style = "color: gray">*No description available.*</span> 

---



<a class="header" id="property-set_editor_setting" href="#property-set_editor_setting">**<span class="hljs-attribute">func</span> [<span class="hljs-title">set_editor_setting</span>](#property-set_editor_setting) ( `setting`: [String](https://docs.godotengine.org/en/latest/classes/class_string.html#class-string), `value`: [Variant](https://docs.godotengine.org/en/latest/classes/class_variant.html#class-variant) )</a>  ⇒ <span style = "color: gray">void</span>** 



 <span style = "color: gray">*No description available.*</span> 

---



<a class="header" id="property-setup_script_property_edit_node" href="#property-setup_script_property_edit_node">**<span class="hljs-attribute">func</span> [<span class="hljs-title">setup_script_property_edit_node</span>](#property-setup_script_property_edit_node) ( `property_info`: [Dictionary](https://docs.godotengine.org/en/latest/classes/class_dictionary.html#class-dictionary), `value`: [Variant](https://docs.godotengine.org/en/latest/classes/class_variant.html#class-variant), `property_changed`: [Callable](https://docs.godotengine.org/en/latest/classes/class_callable.html#class-callable) )</a>  ⇒ <span class="hljs-attribute">[Control](https://docs.godotengine.org/en/latest/classes/class_control.html#class-control)</span>** 



 <span style = "color: gray">*No description available.*</span> 

---



<a class="header" id="property-str_to_bool" href="#property-str_to_bool">**<span class="hljs-attribute">func</span> [<span class="hljs-title">str_to_bool</span>](#property-str_to_bool) ( `boolstring`: [String](https://docs.godotengine.org/en/latest/classes/class_string.html#class-string) )</a>  ⇒ <span class="hljs-attribute">[bool](https://docs.godotengine.org/en/latest/classes/class_bool.html#class-bool)</span>** 



 <span style = "color: gray">*No description available.*</span> 

---



<a class="header" id="property-str_to_hash_set" href="#property-str_to_hash_set">**<span class="hljs-attribute">func</span> [<span class="hljs-title">str_to_hash_set</span>](#property-str_to_hash_set) ( `source`: [String](https://docs.godotengine.org/en/latest/classes/class_string.html#class-string) )</a>  ⇒ <span class="hljs-attribute">[Dictionary](https://docs.godotengine.org/en/latest/classes/class_dictionary.html#class-dictionary)</span>** 



Takes `source` and builds a dictionary of keys only. The values are `null`.

---



<a class="header" id="property-update_autoload_subsystem_access" href="#property-update_autoload_subsystem_access">**<span class="hljs-attribute">func</span> [<span class="hljs-title">update_autoload_subsystem_access</span>](#property-update_autoload_subsystem_access) ( )</a>  ⇒ <span style = "color: gray">void</span>** 



 <span style = "color: gray">*No description available.*</span> 

---



<a class="header" id="property-update_timer_process_callback" href="#property-update_timer_process_callback">**<span class="hljs-attribute">func</span> [<span class="hljs-title">update_timer_process_callback</span>](#property-update_timer_process_callback) ( `timer`: [Timer](https://docs.godotengine.org/en/latest/classes/class_timer.html#class-timer) )</a>  ⇒ <span style = "color: gray">void</span>** 



 <span style = "color: gray">*No description available.*</span> 

---

