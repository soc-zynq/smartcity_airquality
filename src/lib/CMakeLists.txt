# Create a library called "smartcity_airquality"
add_library(smartcity_airquality_lib smartcity_airquality.cpp)

# Specify include directories for the library
target_include_directories(smartcity_airquality_lib PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/../../include)
