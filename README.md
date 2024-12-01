Platform
  - This is meant to be built and ran on macOS or linux using cmake
  - A windows version with visual studio solution files is avaiable here: https://github.com/enjuk/lab12_windows

Build Instructions
  - Prerequisites: cmake and (clang++ or g++)

  - Execute the following terminal commands from the project directory:
      - cmake -S . -B build
      - cmake --build build
      - ./build/bin/lab12

Warnings
  - I didn't have time to add the ability to cancel an ongoing action or return to the previous page. The only solution is to kill the program.
  - Professors need to have at least one rating stored in the professor_rating.csv file or the program will crash.
  - There is no validation of the data files, so if they are corrupted from outside the program it will likely crash.
  - Working data files are stored in the _default_files directory. Copy them to the main project directory if you need to replace corrupted files.
