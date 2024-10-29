file(GLOB source_files ./*.c ./*.h)
set(SOURCES ${source_files})

add_executable(${PROJECT_NAME} ${SOURCES})
# set(raylib_VERBOSE 1)
target_link_libraries(${PROJECT_NAME} raylib)
