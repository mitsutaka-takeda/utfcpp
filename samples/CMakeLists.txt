add_executable (sample docsample.cpp)

target_compile_options(
  sample
  PRIVATE
  -std=c++11
  )
