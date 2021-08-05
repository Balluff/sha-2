cmake_minimum_required (VERSION 3.15.2)

project(sha-2 VERSION 1.0.0)
set(BASE_DIR "${CMAKE_CURRENT_LIST_DIR}/src")

set(INCLUDES
    ${BASE_DIR}/sha2.hpp
    )

add_library(${PROJECT_NAME} INTERFACE
)

target_link_libraries(${PROJECT_NAME}
)

target_include_directories(${PROJECT_NAME} INTERFACE
                            ${BASE_DIR}
)