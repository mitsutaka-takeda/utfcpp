add_executable (negative negative.cpp)

target_compile_options(
  negative
  PRIVATE
  -std=c++11
  )
