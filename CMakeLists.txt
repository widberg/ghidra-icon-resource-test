cmake_minimum_required(VERSION 3.10)
project(MyApp LANGUAGES CXX)

set(SRC_FILES
    main.cpp
    myapp.rc
)

add_executable(MyApp WIN32 ${SRC_FILES})
