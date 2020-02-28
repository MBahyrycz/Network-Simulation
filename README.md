# Network-Simulation

To test implemented funcionality:  
    1.In CMakeLists.txt in set(SOURCES_FILES_TESTS ...) uncomment * .cpp file with module you want to be tested. (the rest leave    comented !)  
    2.In CmakeLists.txt in target_compile_definitions(sol__test PUBLIC EXERCISE_ID= *id of funcionality to test*) type id of funcionality to test taken from directory: *test/config.hpp*  
    3.Run configuration sol__test
