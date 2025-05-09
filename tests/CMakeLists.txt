add_executable(test_all
    test_csv_loader.cpp
    test_backtester.cpp
)
target_link_libraries(test_all PRIVATE Catch2::Catch2WithMain oddscore)
include(CTest)
add_test(NAME all_tests COMMAND test_all)