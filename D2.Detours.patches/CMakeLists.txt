# We embed the patching ordinal information directly into the .DLLs

D2MOO_add_detours_patch_to_dll(Fog)
D2MOO_add_detours_patch_to_dll(D2Common)
D2MOO_add_detours_patch_to_dll(D2Game)
D2MOO_add_detours_patch_to_dll(D2Debugger)

set_property(DIRECTORY ${D2MOO_SOURCE_DIR} PROPERTY VS_STARTUP_PROJECT D2Debugger)
