# V8-Precompiled
Prebuilt monolithic libraries for Google's V8 (version 6.7)

Compiled with visual studio 2015 for embedding V8 in C++. Both x64 and x86 libs are compiled.
This is a monolithic library so linking to single library v8_monolith.lib will suffice instead of linking to multiple v8_libbase.lib v8_base_0.lib etc. Library is compiled to require no external file snapshots, icudtl etc.

Release library is compiled with following flags:

is_debug = false  
enable_nacl = false  
enable_nacl_nonsfi = false  
icu_use_data_file = false  
is_component_build = false  
is_official_build = true  
msan_track_origins = 0  
symbol_level = 0  
use_udev = false  
v8_enable_i18n_support = false  
v8_use_external_startup_data = false  
v8_static_library = true  
v8_monolithic = true  
v8_use_snapshot = false  
