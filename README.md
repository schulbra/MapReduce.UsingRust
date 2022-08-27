# MapReduce.UsingRust

//--------------------------------------------------------------------------//


- This program processes input numbers to produce a sum.
  - Program can create two threads, each running the map_data() function.
  - generate_data(): creates vector of vals serving as input for entire prog.
  - partition_data_in_two(): segments input into two partitions.
  - map_data(): map step that provides intermediate sum of partition values.
  - reduce_data(): reduce step for summing of all input values.
  - partition_data(): Partitions input into equal-sized partitions based on the 
  arg num_partitions.
  
- To compile program on the command line type:
 
    " rustc main.rs "

- To run program on the command line type:
 
    " ./main num_partitions num_elements "
    
- Ex:
 
    " ./main 1 30 "
    
    
//--------------------------------------------------------------------------//
