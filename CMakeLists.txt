cmake_minimum_required(VERSION 3.25)
project(lab12 LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_EXPORT_COMPILE_COMMANDS ON)
set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR}/bin)

# include_directories(include)

set(SOURCE_FILES
    Source.cpp
    TUI.hpp
    Page.cpp
    LandingPage.cpp
    LoginPage.cpp
    RegisterAccountPage.cpp
    MainMenuPage.cpp
    CourseSelectionPage.cpp
    RegisterProfessorSelectPage.cpp
    ProfessorLookupPage.cpp
    ProfessorInfoPage.cpp
    CourseLookupPage.cpp
    CourseInfoPage.cpp
    StudentInfoPage.cpp
    RateProfessorPage.cpp
    Controller.cpp
    Student.cpp
    StudentTable.cpp
    Professor.cpp
    ProfessorTable.cpp
    CourseTable.cpp
)

add_executable(${PROJECT_NAME} ${SOURCE_FILES})
