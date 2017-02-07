Baseline DFSIO test for i2.8xlarge with 8x ephemeral drives:

TestDFSIO -write -nrFiles 64 -fileSize 16GB -resFile /tmp/TestDFSIOwrite.txt
TestDFSIO -read -nrFiles 64 -fileSize 16GB -resFile /tmp/TestDFSIOwrite.txt
