include_directories(../Inc)

set(LIB Lib/error.c)
set(SRC_LIST daytimetcpcli.c)
# aux_source_directory(. SRC_LIST)

add_executable(main ${SRC_LIST} ${LIB})
# add_definitions(-D__USE_XOPEN2K8)

set(EXECUTABLE_OUTPUT_PATH ${PROJECT_SOURCE_DIR}/bin)
