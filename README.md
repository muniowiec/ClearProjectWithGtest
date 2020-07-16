# ClearProjectWithGtest

In other directory:

git clone https://github.com/google/googletest/

Copy the googletest repository folder your cloned earlier into the lib/ folder.


To change project name, in main CMakeLists.txt change line:

project(ProjectWithGtest)


To compile project:
mkdir build; cd build; cmake .. -DCMAKE_BUILD_TYPE=Debug -G "Unix Makefiles" 
make all

$ find . -executable -type f
./tst/ProjectWithGtest_tst
./src/ProjectWithGtest_run

Run all the things
If all went well, the code should run:

./src/ProjectWithGtest_run


