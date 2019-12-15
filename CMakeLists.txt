add_subdirectory(el)
add_subdirectory(sc)
install(DIRECTORY HelpSource
        DESTINATION share/SuperCollider/Extensions/scide_scel/)
