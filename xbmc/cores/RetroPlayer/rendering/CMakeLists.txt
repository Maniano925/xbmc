set(SOURCES GUIRenderSettings.cpp
            RPRenderManager.cpp
)

set(HEADERS GUIRenderSettings.h
            IRenderSettingsCallback.h
            RPRenderManager.h
)

core_add_library(rp-rendering)
