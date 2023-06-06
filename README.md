# Static DCT Blocking Simulation

This repository provides a MATLAB simulation for static DCT (Discrete Cosine Transform) blocking. The simulation allows customization of DCT coefficients and supports several static blocking sizes, including 4x4, 8x8, and 16x16.

## What is Static DCT Blocking?

Static DCT blocking is a technique used in image and video compression algorithms. It involves dividing an image or video frame into fixed-size blocks and applying the DCT on each block individually. The DCT converts spatial information into frequency information, enabling efficient compression by representing the image or video in terms of its frequency components.

By employing static DCT blocking, the compression algorithm can exploit the similarity of frequency content within a block. Smaller block sizes, such as 4x4, capture more local details but result in larger compression artifacts. On the other hand, larger block sizes, such as 16x16, capture more global features but may lose finer details. The choice of block size depends on the specific requirements of the application.

## Simulation Features

This simulation offers the following features:

1. Customization of DCT coefficients: Users can modify the DCT coefficients to experiment with different compression effects. The coefficients determine the contribution of each frequency component to the reconstructed image or video.

2. Support for multiple blocking sizes: The simulation supports three static blocking sizes: 4x4, 8x8, and 16x16. Users can choose the desired block size according to their preference or application requirements.

## Getting Started

To run the simulation, follow these steps:

1. Clone this repository to your local machine or download it as a ZIP file.

2. Ensure you have MATLAB installed on your system.

3. Open the MATLAB application and navigate to the directory where you cloned or extracted the repository.

4. Open the `dct_simulation.m` file in MATLAB.

5. Run the simulation by executing the `dct_simulation` script.

6. Modify the DCT coefficients as desired to experiment with different compression effects.

7. The simulation will generate the compressed output and display the reconstructed image.

## License

This simulation is released under the [MIT License](LICENSE).

## Contribution

Contributions to this project are welcome
