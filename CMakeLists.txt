cmake_minimum_required(VERSION 3.15)
project(Actions)

find_package(Python3 COMPONENTS Development REQUIRED)

get_cmake_property(_variableNames VARIABLES)
list (SORT _variableNames)
foreach (_variableName ${_variableNames})
    message(STATUS "${_variableName}=${${_variableName}}")
endforeach()
