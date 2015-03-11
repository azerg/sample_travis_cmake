add_executable (Simple simple.cxx)

include_directories ("${PROJECT_SOURCE_DIR}/simpleLib")
target_link_libraries (Simple simpleLib)
