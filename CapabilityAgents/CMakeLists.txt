cmake_minimum_required(VERSION 3.0)
project(CapabilityAgents LANGUAGES CXX)

include(../build/BuildDefaults.cmake)

add_subdirectory("AIP")
add_subdirectory("Alerts")
add_subdirectory("AudioPlayer")
add_subdirectory("PlaybackController")
add_subdirectory("SpeechSynthesizer")
add_subdirectory("Settings")
add_subdirectory("System")
