
<div class="header-banner purple">
<div class="header-label purple">subsystem_audio</div>
</div>

*This contains the source code documentation of the class `subsystem_audio`.*
        
# subsystem_audio
**Inherits:** [DialogicSubsystem](class_dialogicsubsystem.md)

##################################################################################################
## Properties
Name | Type | Default 
--- | --- | --- 
base_music_player | [AudioStreamPlayer](https://docs.godotengine.org/en/latest/classes/class_audiostreamplayer.html#class-audiostreamplayer) |   
base_sound_player | [AudioStreamPlayer](https://docs.godotengine.org/en/latest/classes/class_audiostreamplayer.html#class-audiostreamplayer) |   
--- 

## Methods
Returns | Method 
--- | --- 
<span style = "color: gray">void</span> | [<span class="hljs-title">clear_game_state</span>](#property-clear_game_state) ( `clear_flag`: [int](https://docs.godotengine.org/en/latest/classes/class_int.html#class-int) = `0` ) 
<span class="hljs-attribute">[bool](https://docs.godotengine.org/en/latest/classes/class_bool.html#class-bool)</span> | [<span class="hljs-title">has_music</span>](#property-has_music) ( ) 
<span style = "color: gray">void</span> | [<span class="hljs-title">interpolate_volume_linearly</span>](#property-interpolate_volume_linearly) ( `value`: [float](https://docs.godotengine.org/en/latest/classes/class_float.html#class-float), `node`: [Node](https://docs.godotengine.org/en/latest/classes/class_node.html#class-node) ) 
<span class="hljs-attribute">[bool](https://docs.godotengine.org/en/latest/classes/class_bool.html#class-bool)</span> | [<span class="hljs-title">is_music_playing_resource</span>](#property-is_music_playing_resource) ( `resource_path`: [String](https://docs.godotengine.org/en/latest/classes/class_string.html#class-string) ) 
<span style = "color: gray">void</span> | [<span class="hljs-title">load_game_state</span>](#property-load_game_state) ( `load_flag`: [int](https://docs.godotengine.org/en/latest/classes/class_int.html#class-int) = `0` ) 
<span style = "color: gray">void</span> | [<span class="hljs-title">pause</span>](#property-pause) ( ) 
<span style = "color: gray">void</span> | [<span class="hljs-title">play_sound</span>](#property-play_sound) ( `path`: [String](https://docs.godotengine.org/en/latest/classes/class_string.html#class-string), `volume`: [float](https://docs.godotengine.org/en/latest/classes/class_float.html#class-float) = `0.0`, `audio_bus`: [String](https://docs.godotengine.org/en/latest/classes/class_string.html#class-string) = `"Master"`, `loop`: [bool](https://docs.godotengine.org/en/latest/classes/class_bool.html#class-bool) = `false` ) 
<span style = "color: gray">void</span> | [<span class="hljs-title">resume</span>](#property-resume) ( ) 
<span style = "color: gray">void</span> | [<span class="hljs-title">stop_all_sounds</span>](#property-stop_all_sounds) ( ) 
<span style = "color: gray">void</span> | [<span class="hljs-title">update_music</span>](#property-update_music) ( `path`: [String](https://docs.godotengine.org/en/latest/classes/class_string.html#class-string) = `""`, `volume`: [float](https://docs.godotengine.org/en/latest/classes/class_float.html#class-float) = `0.0`, `audio_bus`: [String](https://docs.godotengine.org/en/latest/classes/class_string.html#class-string) = `"Master"`, `fade_time`: [float](https://docs.godotengine.org/en/latest/classes/class_float.html#class-float) = `0.0`, `loop`: [bool](https://docs.godotengine.org/en/latest/classes/class_bool.html#class-bool) = `true` ) 
--- 

## Signals


<a class="header" id="signal-music_started" href="#signal-music_started">**<span class="hljs-attribute">signal</span> [<span class="hljs-title">music_started</span>](#signal-music_started) ( `info`: [Dictionary](https://docs.godotengine.org/en/latest/classes/class_dictionary.html#class-dictionary) )** </a>



 <span style = "color: gray">*No description available.*</span> 

---



<a class="header" id="signal-sound_started" href="#signal-sound_started">**<span class="hljs-attribute">signal</span> [<span class="hljs-title">sound_started</span>](#signal-sound_started) ( `info`: [Dictionary](https://docs.godotengine.org/en/latest/classes/class_dictionary.html#class-dictionary) )** </a>



 <span style = "color: gray">*No description available.*</span> 

---

## Property Descriptions



<a class="header" id="property-clear_game_state" href="#property-clear_game_state">**<span class="hljs-attribute">func</span> [<span class="hljs-title">clear_game_state</span>](#property-clear_game_state) ( `clear_flag`: [int](https://docs.godotengine.org/en/latest/classes/class_int.html#class-int) = `0` )</a>  ⇒ <span style = "color: gray">void</span>** 



 <span style = "color: gray">*No description available.*</span> 

---



<a class="header" id="property-has_music" href="#property-has_music">**<span class="hljs-attribute">func</span> [<span class="hljs-title">has_music</span>](#property-has_music) ( )</a>  ⇒ <span class="hljs-attribute">[bool](https://docs.godotengine.org/en/latest/classes/class_bool.html#class-bool)</span>** 



 <span style = "color: gray">*No description available.*</span> 

---



<a class="header" id="property-interpolate_volume_linearly" href="#property-interpolate_volume_linearly">**<span class="hljs-attribute">func</span> [<span class="hljs-title">interpolate_volume_linearly</span>](#property-interpolate_volume_linearly) ( `value`: [float](https://docs.godotengine.org/en/latest/classes/class_float.html#class-float), `node`: [Node](https://docs.godotengine.org/en/latest/classes/class_node.html#class-node) )</a>  ⇒ <span style = "color: gray">void</span>** 



 <span style = "color: gray">*No description available.*</span> 

---



<a class="header" id="property-is_music_playing_resource" href="#property-is_music_playing_resource">**<span class="hljs-attribute">func</span> [<span class="hljs-title">is_music_playing_resource</span>](#property-is_music_playing_resource) ( `resource_path`: [String](https://docs.godotengine.org/en/latest/classes/class_string.html#class-string) )</a>  ⇒ <span class="hljs-attribute">[bool](https://docs.godotengine.org/en/latest/classes/class_bool.html#class-bool)</span>** 



Returns whether the currently playing audio resource is the same as this event's `resource_path`.

---



<a class="header" id="property-load_game_state" href="#property-load_game_state">**<span class="hljs-attribute">func</span> [<span class="hljs-title">load_game_state</span>](#property-load_game_state) ( `load_flag`: [int](https://docs.godotengine.org/en/latest/classes/class_int.html#class-int) = `0` )</a>  ⇒ <span style = "color: gray">void</span>** 



 <span style = "color: gray">*No description available.*</span> 

---



<a class="header" id="property-pause" href="#property-pause">**<span class="hljs-attribute">func</span> [<span class="hljs-title">pause</span>](#property-pause) ( )</a>  ⇒ <span style = "color: gray">void</span>** 



 <span style = "color: gray">*No description available.*</span> 

---



<a class="header" id="property-play_sound" href="#property-play_sound">**<span class="hljs-attribute">func</span> [<span class="hljs-title">play_sound</span>](#property-play_sound) ( `path`: [String](https://docs.godotengine.org/en/latest/classes/class_string.html#class-string), `volume`: [float](https://docs.godotengine.org/en/latest/classes/class_float.html#class-float) = `0.0`, `audio_bus`: [String](https://docs.godotengine.org/en/latest/classes/class_string.html#class-string) = `"Master"`, `loop`: [bool](https://docs.godotengine.org/en/latest/classes/class_bool.html#class-bool) = `false` )</a>  ⇒ <span style = "color: gray">void</span>** 



Plays a given sound file.

---



<a class="header" id="property-resume" href="#property-resume">**<span class="hljs-attribute">func</span> [<span class="hljs-title">resume</span>](#property-resume) ( )</a>  ⇒ <span style = "color: gray">void</span>** 



 <span style = "color: gray">*No description available.*</span> 

---



<a class="header" id="property-stop_all_sounds" href="#property-stop_all_sounds">**<span class="hljs-attribute">func</span> [<span class="hljs-title">stop_all_sounds</span>](#property-stop_all_sounds) ( )</a>  ⇒ <span style = "color: gray">void</span>** 



 <span style = "color: gray">*No description available.*</span> 

---



<a class="header" id="property-update_music" href="#property-update_music">**<span class="hljs-attribute">func</span> [<span class="hljs-title">update_music</span>](#property-update_music) ( `path`: [String](https://docs.godotengine.org/en/latest/classes/class_string.html#class-string) = `""`, `volume`: [float](https://docs.godotengine.org/en/latest/classes/class_float.html#class-float) = `0.0`, `audio_bus`: [String](https://docs.godotengine.org/en/latest/classes/class_string.html#class-string) = `"Master"`, `fade_time`: [float](https://docs.godotengine.org/en/latest/classes/class_float.html#class-float) = `0.0`, `loop`: [bool](https://docs.godotengine.org/en/latest/classes/class_bool.html#class-bool) = `true` )</a>  ⇒ <span style = "color: gray">void</span>** 



Updates the background music. Will fade out previous music.

---

