# gtest-binary
gtest binary build by cmake

## usage:
Add this project as submodule to your project like:
```bash
git add submodule git@github.com:ly3too/gtest-binary.git ext/gtest
```

Then you can use gtest by find_package:
```cmake
find_package(GTest REQUIRED PATHS ext/gtest/${CMAKE_SYSTEM_NAME} NO_DEFAULT_PATH)
set(GTEST GTest::gtest GTest::gtest_main)
target_link_libraries(test_exe ${GTEST})
```
