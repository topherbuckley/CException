add_library(CException STATIC
    lib/CException.c)

target_include_directories(CException PUBLIC
    ${CMAKE_CURRENT_SOURCE_DIR}/lib)