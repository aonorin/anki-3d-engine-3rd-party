This repository contains all the external libraries for AnKi.

When copying the lua dont copy the 2 .c files that contain the main. you don't
need those

For zlib and libpng just download the source from freeimage library

For assimp buld it first to generate some files, copy code, contrib, include. See the cmake file and do the boost workaround. Remove the cppunit* dir from contrib.