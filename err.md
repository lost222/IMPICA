make ARCH=arm64 CROSS_COMPILE=aarch64-linux-gnu- -C ../linux-aarch64-gem5-20140821 M=/IMPICA/pim_driver modules
make[1]: Entering directory '/IMPICA/linux-aarch64-gem5-20140821'
  CC [M]  /IMPICA/pim_driver/test-driver.o
In file included from include/linux/types.h:5:0,
                 from include/linux/kernel.h:8,
                 from /IMPICA/pim_driver/test-driver.c:1:
include/uapi/linux/types.h:4:23: fatal error: asm/types.h: No such file or directory
 #include <asm/types.h>
                       ^
compilation terminated.
scripts/Makefile.build:263: recipe for target '/IMPICA/pim_driver/test-driver.o' failed
make[2]: *** [/IMPICA/pim_driver/test-driver.o] Error 1
Makefile:1331: recipe for target '_module_/IMPICA/pim_driver' failed
make[1]: *** [_module_/IMPICA/pim_driver] Error 2
make[1]: Leaving directory '/IMPICA/linux-aarch64-gem5-20140821'
Makefile:6: recipe for target 'all' failed
make: *** [all] Error 2
