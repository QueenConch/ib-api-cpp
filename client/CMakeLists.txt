set(PROJECT_NAME client-lib)

file(GLOB client-lib-header "*.h")
file(GLOB client-lib-source "*.cpp")

add_library(${PROJECT_NAME} SHARED ${client-lib-header} ${client-lib-source})