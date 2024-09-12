# Prallel Computing
Parallel image processing application using MPI (Message Passing Interface) in C++.
# The objective:
The objective is to parallelize common image processing operations to achieve faster execution times on a cluster or multi-core system.
# Details:
• Image Loading and Distribution
        o Master node should able to load an input image (e.g., in JPEG or PNG format) anddistribute it across multiple MPI processes.

• Parallel Image processing algorithms that should be implemented
        o Gaussian Blur
        o Edge Detection
        o Image Rotation
        o Image Scaling
        o Color Space Conversion
        o Global Thresholding
        o Local Thresholding
        o Image Compression
        o Median

• Running in a cluster of N>2 (Two machines or more)
