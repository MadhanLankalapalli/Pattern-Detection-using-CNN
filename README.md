# Pattern-Detection-using-CNN
## Abstract

This project presents a **hardware-efficient Convolutional Neural Network (CNN)** implemented entirely at **Register Transfer Level (RTL)** using **Verilog HDL** for real-time object recognition. The system detects and counts occurrences of a predefined **8×8 test pattern** within a **128×128 grayscale image**.  

The proposed CNN architecture employs **Laplacian-based edge enhancement**, **pattern-matching convolution**, **max pooling**, and **threshold-based detection**, optimized using pipelining and parallelism. RTL simulations validate functional correctness, and timing analysis confirms reliable operation at **155.67 MHz**, making the design suitable for **FPGA-based edge AI applications**.

