# Compile
```
gcc -o [output file name] thread_pool.c -pthread
```

## To controll how many threads are created for the thread pool or how long is the task queue, change:
```
#define THREADS_POOL_SIZE x
#define QUEUE_SIZE y
```