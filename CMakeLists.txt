cmake_minimum_required ( VERSION 2.8 )

project ( struct C )
include ( cmake/dist.cmake )
include ( lua )

install_lua_module ( struct struct.c )

install_doc ( struct.html )

install_test ( teststruct.lua )
