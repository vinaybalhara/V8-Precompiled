V8-Precompiled
Prebuilt monolithic static libraries of Google's V8 (version 6.7)

Compiled with visual studio 2015 for embedding V8 in C++. Both x64 and x86 libs are compiled.
This is a monolithic library so linking to single library v8_monolith.lib will suffice instead of linking to multiple v8_libbase.lib v8_base_0.lib etc. Library is compiled to require no external file snapshots, icudtl etc.

Debug library is compiled without debug information and debug symbols to keep size small. In case you need to debug V8 I'll provide the required library with debug symbols.
