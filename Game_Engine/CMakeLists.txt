cmake_minimum_required(VERSION 3.10)

# 项目信息
project(MyProject)

# 设置 C++ 标准
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# 添加源文件
file(GLOB SOURCES "src/*.cpp")

#指定头文件所在的目录
include_directories(include)

# 添加可执行文件
add_executable(MyProject ${SOURCES})


