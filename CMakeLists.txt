cmake_minimum_required(VERSION 3.27)
project(Starter CXX)


build_application(
    SOURCES
    application.cpp

    PACKAGES
    glfw3
    fmt
    glad
    stb
    assimp

    LINK_PACKAGES
    glfw
    fmt::fmt
    glad::glad
    stb::stb
    assimp::assimp
)
