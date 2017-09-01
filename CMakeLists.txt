cmake_minimum_required(VERSION 3.8)
project(OrgaTarea1_master)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        bin/Debug/Tarea1
        archivo_evaluador
        archivo_evualuador
        Evaluador.cpp
        Evaluador.h
        main.cpp
        Mascota.cpp
        Mascota.h
        Tarea1.cbp
        Tarea1.depend
        Tarea1.layout)

add_executable(OrgaTarea1_master ${SOURCE_FILES})