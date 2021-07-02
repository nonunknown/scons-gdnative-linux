# Sconstruct for GDNATIVE

this is the same as provided in godot docs (GDNative C++ example)
except that this one is modified to support compiling in linux for windows.

Example command:
`scons platform=linux -j4 xwin=yes target=release target_name=test.dll`

the parameter `xwin=yes` means that it will x-compile to windows.

`target_name=test.dll` the output file (needs testing maybe using .so will work on windows too).
