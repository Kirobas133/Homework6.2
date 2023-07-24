cmake_minimum_required(VERSION 3.20)
Project(Homework6.2)
#add_executable(Homework6.1ST Homework6.1ST.cpp)

add_subdirectory(../Catch2 Catch2-build)
add_executable(Homework6.2 Homework6.2.cpp)
target_link_libraries(Homework6.2 PRIVATE Catch2::Catch2)