# 1. Create executable
add_executable(buggy buggy.cpp)

add_test(NAME buggy_code COMMAND buggy)

