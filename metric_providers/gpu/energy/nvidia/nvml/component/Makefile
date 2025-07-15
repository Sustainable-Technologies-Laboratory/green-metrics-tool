CFLAGS  = -O3 -Wall -Werror -I../../../../../../lib/c -I/usr/local/cuda-12.9/targets/x86_64-linux/include
LDFLAGS = -L../../../../../../lib/c -lnvidia-ml -lc

metric-provider-binary: source.c
	gcc -O3 -Wall -Werror -I../../../../../../lib/c -I/usr/local/cuda-12.8/targets/x86_64-linux/include ../../../../../../lib/c/gmt-lib.o source.c -L/usr/lib/x86_64-linux-gnu -lnvidia-ml -lc -o metric-provider-binary
