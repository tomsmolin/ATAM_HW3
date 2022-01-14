# ATAM_HW3
Adding a dependencies feature to GNU Make 4.3

In this feature we add support for a --gen-depgraph=FILE flag.
By adding this flag to the make command we print the dependencies as appeared in the MakeFile to FILE 
in the following format:

digraph depgraph {
a -> b;
a -> c;
c -> d;
...
}
