##############################################################################
# Cmake
##############################################################################

cmake_minimum_required(VERSION 2.8.3)
project(groot_mediterranean_themes)

##############################################################################
# Installs
##############################################################################

install(DIRECTORY MediterraneanDark DESTINATION ${CMAKE_INSTALL_PREFIX}/share/themes)
install(DIRECTORY MediterraneanDarkest DESTINATION ${CMAKE_INSTALL_PREFIX}/share/themes)
install(DIRECTORY MediterraneanGrayDark DESTINATION ${CMAKE_INSTALL_PREFIX}/share/themes)
install(DIRECTORY MediterraneanLight DESTINATION ${CMAKE_INSTALL_PREFIX}/share/themes)
install(DIRECTORY MediterraneanLightDarkest DESTINATION ${CMAKE_INSTALL_PREFIX}/share/themes)
install(DIRECTORY MediterraneanNight DESTINATION ${CMAKE_INSTALL_PREFIX}/share/themes)
install(DIRECTORY MediterraneanNightDarkest DESTINATION ${CMAKE_INSTALL_PREFIX}/share/themes)
install(DIRECTORY MediterraneanTribute DESTINATION ${CMAKE_INSTALL_PREFIX}/share/themes)
install(DIRECTORY MediterraneanTributeBlue DESTINATION ${CMAKE_INSTALL_PREFIX}/share/themes)
install(DIRECTORY MediterraneanTributeDark DESTINATION ${CMAKE_INSTALL_PREFIX}/share/themes)
install(DIRECTORY MediterraneanWhite DESTINATION ${CMAKE_INSTALL_PREFIX}/share/themes)
install(DIRECTORY MediterraneanWhiteNight DESTINATION ${CMAKE_INSTALL_PREFIX}/share/themes)
