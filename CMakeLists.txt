cmake_minimum_required(VERSION 3.26)

project(test_library_cpp)

add_library(${PROJECT_NAME} SHARED ${CMAKE_SOURCE_DIR}/src/Test_Library_CPP.cpp)

target_include_directories(${PROJECT_NAME} PUBLIC ${CMAKE_SOURCE_DIR}/include)

