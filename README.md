# Simple benchmark of read and fread
This is a simple benchmark to compare the performance of read function and fread function from c lang.

# Benchmark Result 
As expected fread (buffred read) is more effecient than read specialy for large files.

```
testRead        0.056000
testFread       0.041000
testFreadWithBuffer     0.033000

Process returned 0 (0x0)   execution time : 0.144 s
Press any key to continue.
```