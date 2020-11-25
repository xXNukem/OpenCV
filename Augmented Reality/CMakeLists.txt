cmake_minimum_required(VERSION 3.10)
project( hello_world_opencv )
find_package( OpenCV REQUIRED )

#SET(OpenCV_DIR /home/carlos/Escritorio/installation/OpenCV-master/lib/cmake/opencv4)

#add_executable( hello_world_opencv hello_world_opencv.cpp )
#target_link_libraries( hello_world_opencv ${OpenCV_LIBS})

#---MODO DE USO
#add_executable(nombre_proyecto fichero_codigo1.cpp fichero_codigo2.cpp ...)
#target_link_libraries(nombre_proyecto ${OpenCV_LIBS})
#---COMPILACION
#Crear carpeta Build dentro de la carpeta del proyecto
#Ejecutar cmake.. desde la carpeta build
#Ejecutar make desde la carpeta build
add_executable( augRe augRe.cpp )
target_link_libraries( augRe ${OpenCV_LIBS})

