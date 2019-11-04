


# MapReduce 
- This allows programmers without any experience with parallel and distributed systems to easily utilize the resources of a large distributed system.
- Master failure is not addressed
- Network Bandwith is a scarcity, data locality is key.
- Atomic rename operation provided by underlying file system to guarentee that the final file state contains just the data produced by one execution of the reduce task. 
- Zipf? Skipping bad Records is good. 
- First time sort 1TB of data < 10 minutes>


# GFS
- Provides fault tolerance and runs on inexpensive commodity hardware. 
- Multi-GB files are common;
- Unique 64 bit chunks on chunkserver
- Mark and sweep later for garbage collection. Marked as Hidden
- 3 Replications