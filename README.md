# Awesome-learned-index

This is a collection of learned index papers w/o notes.

## By year

### 2018

1. [2018-The case for learned index](papers/2018-google-learned-index.pdf): the first learned index paper. It introduces RMI that use tree-like structures. Inner nodes are models while leaf nodes are data. Each model maps from a key $k$ to a position $p$($k\rightarrow p$).

### 2019

1. [2019-SOSD_Benchmark](papers/2019-SOSD_Benchmark.pdf)

2. [2019-arxiv-Scalable_Learned_Index_in_Storage](papers/2019-arxiv-Scalable_Learned_Index_in_Storage.pdf):  the initial version of FINEdex

3. [2019-SIGMOD-FITing-Tree_Data-aware-Index](papers/2019-SIGMOD-FITing-Tree_Data-aware-Index.pdf)

### 2020

1. [2020-aiDM-Radix_Spline](papers/2020-aiDM-Radix_Spline.pdf): Using linear spine fits to a CDF, then a flat radix table as an appoximate index.
2. [2020-APSys-SIndex_Scalable_Learned_Index__String_Keys](papers/2020-APSys-SIndex_Scalable_Learned_Index__String_Keys.pdf)
3. [2020-ICDEW-SMART-Self_Tuning_ART](papers/2020-ICDEW-SMART-Self_Tuning_ART.pdf)
4. [2020-OSDI-Bourbon_learned_LSM](papers/2020-OSDI-Bourbon_learned_LSM.pdf)
5. [2020-OSDI-Bourbon_learned_LSM_slides](papers/2020-OSDI-Bourbon_learned_LSM_slides.pdf)
6. [2020-PPoPP-XIndex_Scalable_Learned_Index_for_Multicore_Data_Storage](papers/2020-PPoPP-XIndex_Scalable_Learned_Index_for_Multicore_Data_Storage.pdf)
7. [2020-SIGMOD-ALEX_Updatable_Adaptive_Learned_Index](2020-SIGMOD-ALEX_Updatable_Adaptive_Learned_Index.pdf)
8. [2020-SIGMOD-CDFShop-Exploring_and_Optimizing_Learned_Index_Structures](papers/2020-SIGMOD-CDFShop-Exploring_and_Optimizing_Learned_Index_Structures.pdf): tuning parameters of RMIs
9. [2020-VLDB-PGM-index_fully-dynamic_compressed_worst-case_bounds](papers/2020-VLDB-PGM-index_fully-dynamic_compressed_worst-case_bounds.pdf)
10. [2020-workshop_NIPS_Learned_Index_for_bigtable](papers/2020-workshop_NIPS_Learned_Index_for_bigtable.pdf)

### 2021

1. [2021-PVLDB-Benchmarking_Learned_Indexes](papers/2021-PVLDB-Benchmarking_Learned_Indexes.pdf)
1. [2021-PVLDB-FINEdex-Fine-grained_for_Scalable_Concurrent_Memory_Systems](papers/2021-PVLDB-FINEdex-Fine-grained_for_Scalable_Concurrent_Memory_Systems.pdf)

### 2022

1. [2022-VLDB-NFL_Learned_Index_Distribution_Transformation](papers/2022-VLDB-NFL_Learned_Index_Distribution_Transformation.pdf): it transforms keys distribution to make it more linear. [source code](https://github.com/luffy06/NFL)

## By category

### Survey/Benchmark

1. [2019-SOSD_Benchmark](papers/2019-SOSD_Benchmark.pdf)
2. [2021-PVLDB-Benchmarking_Learned_Indexes](papers/2021-PVLDB-Benchmarking_Learned_Indexes.pdf)
3. [2022-are_updatable_learned_index_ready](papers/2022-are_updatable_learned_index_ready.pdf)

### Read-only

1. [The case for learned index](papers/2018-google-learned-index.pdf)
2. [2020-aiDM-Radix_Spline](papers/2020-aiDM-Radix_Spline.pdf)

### Updatable

1. [2020-SIGMOD-ALEX_Updatable_Adaptive_Learned_Index](papers/2020-SIGMOD-ALEX_Updatable_Adaptive_Learned_Index.pdf) Use gapped array for SMO
2. [2020-VLDB-PGM-index_fully-dynamic_compressed_worst-case_bounds](papers/2020-VLDB-PGM-index_fully-dynamic_compressed_worst-case_bounds.pdf)
3. [2021-AIDB-PLEX_RS+CHT](papers/2021-AIDB-PLEX_RS+CHT.pdf): RadixSpine as the top + Compact Hist-Tree as the bottom
4. [2021-PVLDB-LIPP_Updatable Learned_Index_Precise_Positions](papers/2021-PVLDB-LIPP_Updatable Learned_Index_Precise_Positions.pdf)

### Secondary Storage/Persistent Memory

1. [2019-arxiv-Scalable_Learned_Index_in_Storage](papers/2019-arxiv-Scalable_Learned_Index_in_Storage.pdf): the initial version of FINEdex

2. [2020-workshop_NIPS_Learned_Index_for_bigtable](papers/2020-workshop_NIPS_Learned_Index_for_bigtable.pdf)

3. [2020-OSDI-Bourbon_learned_LSM](papers/2020-OSDI-Bourbon_learned_LSM.pdf)

4. [2020-OSDI-Bourbon_learned_LSM_slides](papers/2020-OSDI-Bourbon_learned_LSM_slides.pdf)

5. [2022-aiDM-LSI-Learned_Secondary_Index_Structure](papers/2022-aiDM-LSI-Learned_Secondary_Index_Structure.pdf)

6. [2022-VLDB-APEX_Learned_Index_PM](papers/2022-VLDB-APEX_Learned_Index_PM.pdf)

### Radix-Spine based

1. [2020-aiDM-Radix_Spline](papers/2020-aiDM-Radix_Spline.pdf): Using linear spine fits to a CDF, then a flat radix table as an appoximate index.
2. [2021-AIDB-RSS_Bounding_the_Last_Mile-Efficient_Learned_String_Indexing](papers/2021-AIDB-RSS_Bounding_the_Last_Mile-Efficient_Learned_String_Indexing.pdf)
3. [2021-AIDB-PLEX_RS+CHT](papers/2021-AIDB-PLEX_RS+CHT.pdf)

### Variable length string keys

1. [2020-APSys-SIndex_Scalable_Learned_Index__String_Keys](papers/2020-APSys-SIndex_Scalable_Learned_Index__String_Keys.pdf)
2. [2021-AIDB-RSS_Bounding_the_Last_Mile-Efficient_Learned_String_Indexing](papers/2021-AIDB-RSS_Bounding_the_Last_Mile-Efficient_Learned_String_Indexing.pdf)

### Concurrency

1. [2020-PPoPP-XIndex_Scalable_Learned_Index_for_Multicore_Data_Storage](papers/2020-PPoPP-XIndex_Scalable_Learned_Index_for_Multicore_Data_Storage.pdf)
1. [2020-APSys-SIndex_Scalable_Learned_Index_String_Keys](papers/2020-APSys-SIndex_Scalable_Learned_Index_String_Keys.pdf)
1. [2021-PVLDB-FINEdex-Fine-grained_for_Scalable_Concurrent_Memory_Systems](papers/2021-PVLDB-FINEdex-Fine-grained_for_Scalable_Concurrent_Memory_Systems.pdf)
1. [2022-TOS-Xindex-most-recent](papers/2022-TOS-Xindex-most-recent.pdf)
