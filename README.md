# ClearProjectWithGtest

git submodule update --init --recursive #to download googletest


To change project name, in main CMakeLists.txt change line:

project(ProjectWithGtest)


To compile project:
cd build; cmake .. -DCMAKE_BUILD_TYPE=Debug -G "Unix Makefiles" 
make all

$ find . -executable -type f
./tst/ProjectWithGtest_tst
./src/ProjectWithGtest_run

Run all the things
If all went well, the code should run:

./src/ProjectWithGtest_run


