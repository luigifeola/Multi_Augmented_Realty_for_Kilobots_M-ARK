include_directories(argos3/plugins/robot/kilobot/control_interface argos3/plugins/robot/kilobot/simulator)

add_library(kilobot_ALF_dhtf_loop_function
  MODULE 
  kilobot_ALF_dhtf.h
  kilobot_ALF_dhtf.cpp
  area.h
)

target_link_libraries(kilobot_ALF_dhtf_loop_function
  argos3core_simulator
  argos3plugin_simulator_dynamics2d
  argos3plugin_simulator_entities
  argos3plugin_simulator_media
  argos3plugin_simulator_kilobot
  argos3plugin_simulator_kilolib
)
