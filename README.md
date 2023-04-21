# JPEG-Compression
Compression for TIF files to jpeg format

This is a repository containing code for JPEG compression. JPEG (Joint Photographic Experts Group) is a commonly used method of lossy compression for digital images, particularly for those images produced by digital photography.

This repository contains an implementation of the JPEG compression algorithm in Python. The algorithm takes an input image and compresses it by reducing the amount of data needed to store the image, while attempting to preserve the visual quality of the image.
Getting Started

To get started with this repository, clone the repository onto your local machine. The code is written in Python and requires Python 3.6 or higher to run. The following libraries are also required:

    numpy
    Pillow

These can be installed using pip:

bash

    pip install numpy
    pip install Pillow

Once you have the code and the required libraries installed, you can run the compression algorithm by running the following command:

bash

    python JPEG.py



The JPEG compression algorithm consists of the following steps:

    Color Space Conversion - Convert the RGB image into YUV color space
    Discrete Cosine Transform - Transform the image from spatial domain to frequency domain
    Quantization - Reduce the number of bits used to represent the DCT coefficients
    ZigZag Encoding - Compress the DCT coefficients using ZigZag encoding

The compressed image is then stored as a series of bits, which can be decompressed using the inverse of the JPEG compression algorithm.
Contributing
