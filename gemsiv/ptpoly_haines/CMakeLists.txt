add_executable(ptpoly_haines ptinpoly.h p_test.c ptinpoly.c)
if(CMAKE_COMPILER_IS_GNUCC)
		target_link_libraries(ptpoly_haines FakeIrisGL m)
else()
		target_link_libraries(ptpoly_haines FakeIrisGL)
endif()

