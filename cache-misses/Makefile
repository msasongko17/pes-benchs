all:	cache-misses-install cache-misses-run

cache-misses-install:	cache_misses_asm_per20.c cache_misses_asm_per40.c cache_misses_asm_per60.c cache_misses_asm_per80.c cache_misses_asm_per100.c
	gcc cache_misses_asm_per20.c -o cache_misses_asm_per20 -fopenmp
	gcc cache_misses_asm_per40.c -o cache_misses_asm_per40 -fopenmp
	gcc cache_misses_asm_per60.c -o cache_misses_asm_per60 -fopenmp
	gcc cache_misses_asm_per80.c -o cache_misses_asm_per80 -fopenmp
	gcc cache_misses_asm_per100.c -o cache_misses_asm_per100 -fopenmp

cache-misses-run-5x: cache-misses-20-run-5x cache-misses-40-run-5x cache-misses-60-run-5x cache-misses-80-run-5x cache-misses-100-run-5x

cache-misses-run: cache-misses-20-run cache-misses-40-run cache-misses-60-run cache-misses-80-run cache-misses-100-run

cache-misses-20-run-5x:
	OMP_NUM_THREADS=1 GOMP_CPU_AFFINITY="0" /usr/bin/time -f "Elapsed Time , %e, system, %S, user, %U, memory, %M" ./cache_misses_asm_per20 2>&1 | tee cache_misses_asm_per20_5x_log
	OMP_NUM_THREADS=1 GOMP_CPU_AFFINITY="0" /usr/bin/time -f "Elapsed Time , %e, system, %S, user, %U, memory, %M" ./cache_misses_asm_per20 2>&1 | tee -a cache_misses_asm_per20_5x_log
	OMP_NUM_THREADS=1 GOMP_CPU_AFFINITY="0" /usr/bin/time -f "Elapsed Time , %e, system, %S, user, %U, memory, %M" ./cache_misses_asm_per20 2>&1 | tee -a cache_misses_asm_per20_5x_log	
	OMP_NUM_THREADS=1 GOMP_CPU_AFFINITY="0" /usr/bin/time -f "Elapsed Time , %e, system, %S, user, %U, memory, %M" ./cache_misses_asm_per20 2>&1 | tee -a cache_misses_asm_per20_5x_log
	OMP_NUM_THREADS=1 GOMP_CPU_AFFINITY="0" /usr/bin/time -f "Elapsed Time , %e, system, %S, user, %U, memory, %M" ./cache_misses_asm_per20 2>&1 | tee -a cache_misses_asm_per20_5x_log

cache-misses-40-run-5x:
	OMP_NUM_THREADS=1 GOMP_CPU_AFFINITY="0" /usr/bin/time -f "Elapsed Time , %e, system, %S, user, %U, memory, %M" ./cache_misses_asm_per40 2>&1 | tee cache_misses_asm_per40_5x_log
	OMP_NUM_THREADS=1 GOMP_CPU_AFFINITY="0" /usr/bin/time -f "Elapsed Time , %e, system, %S, user, %U, memory, %M" ./cache_misses_asm_per40 2>&1 | tee -a cache_misses_asm_per40_5x_log
	OMP_NUM_THREADS=1 GOMP_CPU_AFFINITY="0" /usr/bin/time -f "Elapsed Time , %e, system, %S, user, %U, memory, %M" ./cache_misses_asm_per40 2>&1 | tee -a cache_misses_asm_per40_5x_log
	OMP_NUM_THREADS=1 GOMP_CPU_AFFINITY="0" /usr/bin/time -f "Elapsed Time , %e, system, %S, user, %U, memory, %M" ./cache_misses_asm_per40 2>&1 | tee -a cache_misses_asm_per40_5x_log
	OMP_NUM_THREADS=1 GOMP_CPU_AFFINITY="0" /usr/bin/time -f "Elapsed Time , %e, system, %S, user, %U, memory, %M" ./cache_misses_asm_per40 2>&1 | tee -a cache_misses_asm_per40_5x_log

cache-misses-60-run-5x:
	OMP_NUM_THREADS=1 GOMP_CPU_AFFINITY="0" /usr/bin/time -f "Elapsed Time , %e, system, %S, user, %U, memory, %M" ./cache_misses_asm_per60 2>&1 | tee cache_misses_asm_per60_5x_log
	OMP_NUM_THREADS=1 GOMP_CPU_AFFINITY="0" /usr/bin/time -f "Elapsed Time , %e, system, %S, user, %U, memory, %M" ./cache_misses_asm_per60 2>&1 | tee -a cache_misses_asm_per60_5x_log
	OMP_NUM_THREADS=1 GOMP_CPU_AFFINITY="0" /usr/bin/time -f "Elapsed Time , %e, system, %S, user, %U, memory, %M" ./cache_misses_asm_per60 2>&1 | tee -a cache_misses_asm_per60_5x_log
	OMP_NUM_THREADS=1 GOMP_CPU_AFFINITY="0" /usr/bin/time -f "Elapsed Time , %e, system, %S, user, %U, memory, %M" ./cache_misses_asm_per60 2>&1 | tee -a cache_misses_asm_per60_5x_log
	OMP_NUM_THREADS=1 GOMP_CPU_AFFINITY="0" /usr/bin/time -f "Elapsed Time , %e, system, %S, user, %U, memory, %M" ./cache_misses_asm_per60 2>&1 | tee -a cache_misses_asm_per60_5x_log

cache-misses-80-run-5x:
	OMP_NUM_THREADS=1 GOMP_CPU_AFFINITY="0" /usr/bin/time -f "Elapsed Time , %e, system, %S, user, %U, memory, %M" ./cache_misses_asm_per80 2>&1 | tee cache_misses_asm_per80_5x_log
	OMP_NUM_THREADS=1 GOMP_CPU_AFFINITY="0" /usr/bin/time -f "Elapsed Time , %e, system, %S, user, %U, memory, %M" ./cache_misses_asm_per80 2>&1 | tee -a cache_misses_asm_per80_5x_log
	OMP_NUM_THREADS=1 GOMP_CPU_AFFINITY="0" /usr/bin/time -f "Elapsed Time , %e, system, %S, user, %U, memory, %M" ./cache_misses_asm_per80 2>&1 | tee -a cache_misses_asm_per80_5x_log
	OMP_NUM_THREADS=1 GOMP_CPU_AFFINITY="0" /usr/bin/time -f "Elapsed Time , %e, system, %S, user, %U, memory, %M" ./cache_misses_asm_per80 2>&1 | tee -a cache_misses_asm_per80_5x_log
	OMP_NUM_THREADS=1 GOMP_CPU_AFFINITY="0" /usr/bin/time -f "Elapsed Time , %e, system, %S, user, %U, memory, %M" ./cache_misses_asm_per80 2>&1 | tee -a cache_misses_asm_per80_5x_log

cache-misses-100-run-5x:
	OMP_NUM_THREADS=1 GOMP_CPU_AFFINITY="0" /usr/bin/time -f "Elapsed Time , %e, system, %S, user, %U, memory, %M" ./cache_misses_asm_per100 2>&1 | tee cache_misses_asm_per100_5x_log
	OMP_NUM_THREADS=1 GOMP_CPU_AFFINITY="0" /usr/bin/time -f "Elapsed Time , %e, system, %S, user, %U, memory, %M" ./cache_misses_asm_per100 2>&1 | tee -a cache_misses_asm_per100_5x_log
	OMP_NUM_THREADS=1 GOMP_CPU_AFFINITY="0" /usr/bin/time -f "Elapsed Time , %e, system, %S, user, %U, memory, %M" ./cache_misses_asm_per100 2>&1 | tee -a cache_misses_asm_per100_5x_log
	OMP_NUM_THREADS=1 GOMP_CPU_AFFINITY="0" /usr/bin/time -f "Elapsed Time , %e, system, %S, user, %U, memory, %M" ./cache_misses_asm_per100 2>&1 | tee -a cache_misses_asm_per100_5x_log
	OMP_NUM_THREADS=1 GOMP_CPU_AFFINITY="0" /usr/bin/time -f "Elapsed Time , %e, system, %S, user, %U, memory, %M" ./cache_misses_asm_per100 2>&1 | tee -a cache_misses_asm_per100_5x_log

cache-misses-20-run:
	OMP_NUM_THREADS=1 GOMP_CPU_AFFINITY="0" /usr/bin/time -f "Elapsed Time , %e, system, %S, user, %U, memory, %M" ./cache_misses_asm_per20 2>&1 | tee cache_misses_asm_per20_log
	
cache-misses-40-run:
	OMP_NUM_THREADS=1 GOMP_CPU_AFFINITY="0" /usr/bin/time -f "Elapsed Time , %e, system, %S, user, %U, memory, %M" ./cache_misses_asm_per40 2>&1 | tee cache_misses_asm_per40_log

cache-misses-60-run:
	OMP_NUM_THREADS=1 GOMP_CPU_AFFINITY="0" /usr/bin/time -f "Elapsed Time , %e, system, %S, user, %U, memory, %M" ./cache_misses_asm_per60 2>&1 | tee cache_misses_asm_per60_log

cache-misses-80-run:
	OMP_NUM_THREADS=1 GOMP_CPU_AFFINITY="0" /usr/bin/time -f "Elapsed Time , %e, system, %S, user, %U, memory, %M" ./cache_misses_asm_per80 2>&1 | tee cache_misses_asm_per80_log

cache-misses-100-run:
	OMP_NUM_THREADS=1 GOMP_CPU_AFFINITY="0" /usr/bin/time -f "Elapsed Time , %e, system, %S, user, %U, memory, %M" ./cache_misses_asm_per100 2>&1 | tee cache_misses_asm_per100_log

clean:
	rm cache_misses_asm_per20 cache_misses_asm_per40 cache_misses_asm_per60 cache_misses_asm_per80 cache_misses_asm_per100
