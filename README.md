# NuLat_OldDataCollecting


Step 1: Download and unpack the files

Step 2: Make new build folder within "Source_Nulat"
($ mkdir build4)

Step 3: Go into new build folder and run cmake
($ cd build4)
($ cmake ..)

Step 4: build the program with make (can be slow
($ make)       alternative for multicore ($ make -jN) where N = number of cores

Step 5: Copy extra files from build3 to current build directory

Step 6: Copy extra files from build3/macros to current built directory/macros

Step 7 version1: To run  GUI use ./NuLat
($ ./Nulat)

Step 7 version2: To run data collection use ./Nulat.sh
($ ./NuLat.sh)
-May look frozen and take a few minutes to run
