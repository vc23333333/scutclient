cmake_minimum_required(VERSION 2.4)
project(scutclient C)
ADD_DEFINITIONS(-Os -Wall)
add_executable(scutclient src/auth.c src/drcom.c src/functions.c src/info.c src/main.c src/md5.c src/tracelog.c)
install(TARGETS scutclient RUNTIME DESTINATION bin)
