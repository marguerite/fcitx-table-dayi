set(ICON64 fcitx-dayi3.png fcitx-dayi4.png)

install(FILES
    ${ICON64}
    DESTINATION share/icons/hicolor/64x64/apps)

foreach(icon ${ICON64})
    string(REPLACE "fcitx-" "" icon_new ${icon})
    install(FILES ${icon} RENAME ${icon_new} DESTINATION share/fcitx/imicon)
endforeach()
