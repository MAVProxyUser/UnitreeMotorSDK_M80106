cmake_minimum_required(VERSION 3.0.0)
project(UnitreeMotorSDK_M80106)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11 -O3")

include_directories("include")
link_directories(lib)

#example
add_executable(motorctrl src/main.cpp)
target_link_libraries(motorctrl UnitreeMotorSDK_M80106_Linux64)
