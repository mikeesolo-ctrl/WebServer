cmake_minimum_required(VERSION 3.20)
project(web_server)

set(CMAKE_CXX_STANDARD 17)

add_executable(web_server src/main.cpp
        src/Server.cpp
        src/Socket.cpp
        src/HttpRequest.cpp
        include/Server.h
        include/Socket.h
        include/HttpRequest.h
        include/Logger.h)
