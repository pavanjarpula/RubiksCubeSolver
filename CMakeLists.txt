cmake_minimum_required(VERSION 3.30)
project(RubiksCubeSolver)

set(CMAKE_CXX_STANDARD 20)

add_executable(RubiksCubeSolver main.cpp
        RubiksCube.cpp
        Model/RubiksCube.h
        Model/RubiksCube1dArray.cpp
        Model/RubiksCube3dArray.cpp
        Model/RubiksCubeBitboard.cpp
        PatternDatabasas/CornerDBmaker.cpp
        PatternDatabasas/CornerDBmaker.h
        PatternDatabasas/CornerPatternDatabase.cpp
        PatternDatabasas/CornerPatternDatabase.h
        PatternDatabasas/NibbleArray.cpp
        PatternDatabasas/NibbleArray.h
        PatternDatabasas/PatternDatabase.cpp
        PatternDatabasas/PatternDatabase.h
)
