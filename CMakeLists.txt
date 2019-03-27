cmake_minimum_required(VERSION 3.7)
project(systemC_basic)

set(CMAKE_CXX_STANDARD 14)

add_executable(systemC_basic helloworld.cpp)

include_directories("/usr/local/systemc233/include")
target_link_libraries(systemC_basic "/usr/local/systemc233/lib-linux64/libsystemc.a")