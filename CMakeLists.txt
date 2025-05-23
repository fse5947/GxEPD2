cmake_minimum_required(VERSION 3.15)

idf_component_register(SRCS "src/GxEPD2_EPD.cpp" "src/epd/GxEPD2_290_BS.cpp"
                      INCLUDE_DIRS "src" "../Adafruit_BusIO" "../Adafruit-GFX-Library"
                      REQUIRES arduino-esp32
                      )