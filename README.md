# README
## Modifications done for my use case
- disable code completion as I use the microsoft cpp language server. I only use rtags for where used/call hierarchy.
- single click in call hierarchy view now opens the source location
- call hierarchy tree items include file name and line number
- introduce workspace setting `"rtags.rcExecutable"` to specify path to the rc executable
- command updateCompileCommands
- call hierarchy uses now rc argument "all-targets" to include all where used entries

## This is the README for the "rtags client" 
-------------------

This extension provides an interface to the excellent rtags server (https://github.com/Andersbakken/rtags).
To use this extension you have to install rtags and run the rdm binary yourself.

The extension provides C++
* code completion
* finding references
* symbol provider (find symbols)
* symbol renaming
* code action (fix its)
* type definition provider (go to definition)

