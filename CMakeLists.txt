set(COMPONENT_SRCS GD2.cpp)
set(COMPONENT_ADD_INCLUDEDIRS ".")

set(COMPONENT_REQUIRES "arduino-esp32")

register_component()
component_compile_options(-DARDUINO)
component_compile_options(-DESP32)
