LuaJIT decompiler (or more of a bytecode re-assembler)
======================================================

Here's a thing I done made that re-assembles LuaJIT from it's assembly-bytecode (or when used with LuaJIT itself can decompile LuaJIT files)


## If you have any questions on how to use it then read the wiki ##

## This version is good enough for me (at the moment) so I don't think I will be updating it any time soon ##
Things that still need to be added:
* table lookups
* uget lookups (if thats possible?)

By using this you agree that you will not modify anything for malicious purposes, or redistribute source code (decompiled or not) of anything using LuaJIT

addition：
First Install autoit by autoit-v3-setup.exe
add your lua file to data/luajit
run jitdecomp.au3

if your jit version is not 2.1b2,compile jit and copy lua51.dll,luajit.exe,jit foler to root folder