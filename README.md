herein lies builds for:
 BlackParrot: BP
 Hammerblade: HB
 RapidChiplet: RC
as a means for evaluating specific chiplet configurations of two RISC-V chips. 
This configuratoin can be used to determine optimal solutions from offloading deterministic, continous tasks from the coherence engine all the way up to VLM level edge AI chip sets. HB cores can allo be used for lower SWAP tasksa that do not need Cache Coherence. 
Specific examples for deterministic use (no cache miss variability) are control loops and sensor fusion, IO (de)encryption, etc.

Once optimal solution suggestions are found using rapidChiplet, the integrate booksim and more carefully simulate and verify them. 
