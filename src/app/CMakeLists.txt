# ENC tile render command line interface
add_executable(enc_tile_render enc_tile_render.cpp)
target_link_libraries(enc_tile_render encviz)

# ENC tile render server (TMS)
add_executable(enc_tile_server enc_tile_server.cpp)
target_link_libraries(enc_tile_server encviz)
