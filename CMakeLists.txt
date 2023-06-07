cmake_minimum_required(VERSION 3.25.0)

include_directories("include/")

project(GE2DC VERSION 1.0.0 LANGUAGES C)


add_executable(
    GE2DC
    "src/ge2dc/main.c"
)
