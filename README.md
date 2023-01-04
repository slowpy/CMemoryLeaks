# CMemoryLeaks
memory leaks check of C/C++
linux Sample and Android sample of Sanitize 
## 运行结果

01-03 23:02:48.897 32332 32332 I wrap.sh : ==32336==ERROR: AddressSanitizer: stack-buffer-overflow on address 0xffe20f38 at pc 0xbd6d6675 bp 0xffe20ef8 sp 0xffe20ef4
01-03 23:02:48.897 32332 32332 I wrap.sh : READ of size 4 at 0xffe20f38 thread T0 (b.sanitize.test)
01-03 23:02:48.897 32332 32332 I wrap.sh : AddressSanitizer:DEADLYSIGNAL
01-03 23:02:48.897 32332 32332 I wrap.sh : AddressSanitizer: nested bug in the same thread, aborting.
01-03 23:02:48.947   657  5404 I ActivityManager: Force stopping com.yinlib.sanitize.test appid=10094 user=0: from pid 32359
01-03 23:02:48.948   657  5404 I ActivityManager: Killing 32336:com.yinlib.sanitize.test/u0a94 (adj 0): stop com.yinlib.sanitize.test due to from pid 32359
