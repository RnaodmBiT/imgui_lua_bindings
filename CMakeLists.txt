
add_library(imgui_lua_bindings imgui_lua_bindings.cpp)
target_include_directories(imgui_lua_bindings PUBLIC .)
target_link_libraries(imgui_lua_bindings imgui lua)