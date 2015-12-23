set(CMAKE_LEGACY_CYGWIN_WIN32 0) # Remove when CMake >= 2.8.4 is required
project("To Do List")


add_executable(toDo main.cc
                    ToDo.cc)
