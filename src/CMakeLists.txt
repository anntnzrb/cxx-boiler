set(SRC_FILES
        main.cxx
        #foo.cxx
        )

add_executable(${PROJECT_NAME} ${SRC_FILES})

# .hxx files
target_include_directories(${PROJECT_NAME} PRIVATE
        "${PROJECT_SOURCE_DIR}/include")