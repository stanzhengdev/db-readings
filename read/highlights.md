


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

# How to read papers 
- Three passes 
- Abstract, Bullets, Conclusions

# Cloud Computing
- Elasticity
- Distributed 
- High level abstraction or low level 

# 5 min rule signmod
- [Abstract] Simple  economic  and  performance  arguments  sug-gest  appropriate  lifetimes  for  main  memory  pages and  suggest  optimal  page  sizes.      The  fundamental  tradeoffs are the prices and bandwidths of RAMs and disks.    The analysis indicates that with today's tech-nology, five minutes is a good lifetime for randomly accessed  pages,  one  minute  is  a  good  lifetime  for  two-pass sequentially accessed pages, and 16 KB is a good  size  for  index  pages.    These  rules-of-thumb change   in   predictable   ways   as   technology   ratios change.  They  also  motivate  the  importance  of  the new Kaps,   Maps,   Scans,   and $/Kaps,   $/Maps, $/TBscan metrics.
- Time to access depending how long do you want to remember before accessing stuf has increased
- The Kaps, Maps, and Scans metrics that meas-ure  access  rate  and  price/access  are  becoming  in-creasingly important. 