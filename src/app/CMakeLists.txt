# Add source files
add_executable(${PROJECT_NAME} main.cpp)

# Link the project library
target_link_libraries(${PROJECT_NAME} smartcity_airquality_lib)
