### Baseline DFSIO test for i2.8xlarge with 8x ephemeral drives:


```TestDFSIO -write -nrFiles 64 -fileSize 16GB -resFile /tmp/TestDFSIOwrite.txt```

```TestDFSIO -read -nrFiles 64 -fileSize 16GB -resFile /tmp/TestDFSIOread.txt```


https://discuss.pivotal.io/hc/en-us/articles/200864057-Running-DFSIO-MapReduce-benchmark-test
