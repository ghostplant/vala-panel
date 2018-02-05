configure_file (${CMAKE_CURRENT_SOURCE_DIR}/default.in ${CMAKE_CURRENT_BINARY_DIR}/default)
install(FILES ${CMAKE_CURRENT_BINARY_DIR}/default DESTINATION ${PROFILES_DIR} COMPONENT bin)
install(FILES ${CMAKE_CURRENT_SOURCE_DIR}/org.valapanel.application.desktop DESTINATION ${PROFILES_DIR}/../autostart COMPONENT bin)
