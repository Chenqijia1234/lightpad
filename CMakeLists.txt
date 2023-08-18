cmake_minimum_required(VERSION 3.10)
project(lightpad LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(
    ${PROJECT_NAME}
    "src/main.cpp"
    "src/screen.h"
    "src/ui.h"
    "src/utils.h"
    "src/command.h"
    "src/render/tomorrow-night-bright-cpp.h"
    "src/render/tomorrow-night-bright-js.h"
    "src/awacorn/awacorn.h"
    "src/awacorn/generator.h"
    "src/awacorn/promise.h"
)