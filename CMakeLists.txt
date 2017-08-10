cmake_minimum_required(VERSION 2.8.11)

project(stresstest)

set(SOURCES
    ${SOURCES}
    ${CMAKE_CURRENT_SOURCE_DIR}/CSV/CSVread.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/CSV/write.cpp
    ${CMAKE_CURRENT_SOURCE_DIR}/strerror.cpp)

include_directories(${CMAKE_SOURCE_DIR}/CSV)
