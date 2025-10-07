cmake_minimum_required(VERSION 3.5)
idf_component_register(SRCS "src/GFX_Lite.cpp"
                    INCLUDE_DIRS "src/."
                    REQUIRES "arduino-esp32" # Library requires Arduino
                    )

project(GFX_Lite)