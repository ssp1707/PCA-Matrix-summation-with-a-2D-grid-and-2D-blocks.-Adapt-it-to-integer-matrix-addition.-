# PCA-Matrix-summation-with-a-2D-grid-and-2D-blocks.-Adapt-it-to-integer-matrix-addition.-

## Aim:
To perform matrix addition on CPU and GPU and compare their execution time.

## Procedure:
Follow these steps to compare float and integer calculations on the GPU and host side:

1. Allocate and initialize memory for the input matrices (float and integer) on the host.
2. Allocate memory for the output matrices (float and integer) on the host.
3. Allocate memory for the input matrices (float and integer) on the device (GPU).
4. Allocate memory for the output matrices (float and integer) on the device (GPU).
5. Transfer the input matrices (float and integer) from the host to the device.
6. Define the dimensions of the grid and block for launching the GPU kernel.
7. Launch the kernel for float calculations on the GPU.
8. Synchronize the device to ensure the kernel execution is complete.
9. Copy the output matrix for float calculations from the device to the host.
10. Compare the GPU results for float calculations with the host results.
11. Launch the kernel for integer calculations on the GPU.
12. Synchronize the device to ensure the kernel execution is complete.
13. Copy the output matrix for integer calculations from the device to the host.
14. Compare the GPU results for integer calculations with the host results.
15. Free the memory allocated for the input and output matrices on the device.
16. Free the memory allocated for the input and output matrices on the host.
17. Reset the device.

## Output:
![image](https://github.com/Kavya-Bollineni22/PCA-Matrix-summation-with-a-2D-grid-and-2D-blocks.-Adapt-it-to-integer-matrix-addition.-/assets/75235813/47b13da0-814c-4d4d-9354-63996f193064)

## Result:
The program prints the device information, matrix size, and the execution time for matrix initialization, matrix addition on the host, matrix addition on the device, and memory transfer. Thus, float variables can be opted for better performance.
