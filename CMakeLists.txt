cmake_minimum_required(VERSION 3.8)
project(GameEngine)

set(CMAKE_CXX_STANDARD 17)

# Добавляем директорию src
add_executable(GameEngine src/main.cpp src/Engine.cpp)

