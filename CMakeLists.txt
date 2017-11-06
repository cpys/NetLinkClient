cmake_minimum_required(VERSION 3.6)
project(NetLinkClient)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES src/netlink_client.c)

add_executable(client ${SOURCE_FILES})