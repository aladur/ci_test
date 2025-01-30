cmake_minimum_required(VERSION 3.16)

project(Test
    VERSION 1.0
    DESCRIPTION "A test project"
    LANGUAGES C CXX
)

include(CheckCXXCompilerFlag)

# Specify the C++ standard.
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)

set(CMAKE_AUTOMOC ON)
set(CMAKE_AUTORCC ON)
set(CMAKE_AUTOUIC ON)
set(CMAKE_INCLUDE_CURRENT_DIR ON)

find_package(Qt5 REQUIRED Core Widgets Gui X11Extras PrintSupport)

