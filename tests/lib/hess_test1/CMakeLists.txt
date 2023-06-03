add_executable(hess_test1 test1.cpp)
target_link_libraries(hess_test1 ecpint)

add_test(NAME HessTest1
	 COMMAND hess_test1
	 WORKING_DIRECTORY ${PROJECT_SOURCE_DIR}/tests/lib/hess_test1)
