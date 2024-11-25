# CS419.2-two_pass_algorithm
Implementing the Two-Pass Algorithm for Connected Component Extraction

This implementation extracts connected components from binary images using the two-pass connected components algorithm. It assigns labels to regions in the image based on pixel connectivity, which is defined using either 4-connectivity or 8-connectivity.

The algorithm operates in two primary passes:

First Pass:
Labels pixels and records equivalences between connected components.

Second Pass:
Relabels each pixel using the root label from equivalence classes to ensure consistent labeling.
A Union-Find data structure is employed to efficiently manage equivalence classes and optimize label assignment.
