# gtest-binary
gtest binary build by cmake

## usage:
```cmake
find_package(GTest REQUIRED PATHS ext/gtest/${CMAKE_SYSTEM_NAME} NO_DEFAULT_PATH)
set(GTEST GTest::gtest GTest::gtest_main)
```
