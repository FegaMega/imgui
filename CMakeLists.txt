

target_sources(tOnk
    PRIVATE
        imgui.cpp
        imgui_draw.cpp
        imgui_widgets.cpp
        imgui_demo.cpp
        imgui_tables.cpp
    PUBLIC
    FILE_SET myImGuiHeaders
    TYPE HEADERS
    BASE_DIRS
        ./
    FILES
        imconfig.h
        imgui.h
        imgui_internal.h
        imstb_rectpack.h
        imstb_textedit.h
        imstb_truetype.h
)