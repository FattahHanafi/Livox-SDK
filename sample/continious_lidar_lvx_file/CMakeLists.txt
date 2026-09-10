cmake_minimum_required(VERSION 3.6)

set(DEMO_NAME continious_lidar_lvx_file)
add_executable(${DEMO_NAME} main.cpp lvx_file.cpp)

target_link_libraries(${DEMO_NAME}
        PRIVATE
        ${PROJECT_NAME}_static
        )
