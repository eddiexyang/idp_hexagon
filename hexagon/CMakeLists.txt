# Processor Module: hexagon
ida_add_procmod(hexagon
    SOURCES
        ana.cpp
        emu.cpp
        ins.cpp
        out.cpp
        reg.cpp
        loader.cpp
        ../idaidp.hpp
        common.h
        ins.h
        elfr_hexagon.h
)
