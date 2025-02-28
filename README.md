# ThreadPoolExecutor-FastAPI
- Implemented ThreadPoolExecutor using FastAPI.ThreadPoolExecutor uses defined cpu cores.
- For each task asyncronously.Giving illusion of Parallel processing.Efficient for CPU Bound task (where heavy calculations are are done or ML pipelines are used)
- To achieve true parallelism(each task executing in each core simultaneously)we use ProcessPoolExecutor.
- ProcessPoolExecutor is ideal for I/O Bounded task(we wait for output or performing db operations)

# Code:
In file
