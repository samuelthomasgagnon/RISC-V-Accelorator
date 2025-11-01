herein lies builds for:
 BlackParrot: BP https://github.com/black-parrot/black-parrot
 Hammerblade: HB https://github.com/bespoke-silicon-group/bsg_bladerunner/blob/main/README.md
 RapidChiplet: RC https://github.com/spcl/rapidchiplet
as a means for evaluating specific chiplet configurations of two RISC-V chips. 
This configuratoin can be used to determine optimal solutions from offloading deterministic, continous tasks from the coherence engine all the way up to VLM level edge AI chip sets. HB cores can allo be used for lower SWAP tasksa that do not need Cache Coherence. 
Specific examples for deterministic use (no cache miss variability) are control loops and sensor fusion, IO (de)encryption, etc.

The HB many core can be configured in many ways and the optimal tile size may be depend on the task, allowing for optimizatoin in this is critical.

Once optimal solution suggestions are found using rapidChiplet, the integrate booksim and more carefully simulate and verify them. 
