# Crypto-Embed
# Image Steganography System

## Introduction

Image Steganography System is a tool designed to hide secret messages within digital images. Steganography is the practice of concealing secret information within a cover object (CO) in such a way that it is difficult to detect or decipher. This system provides a secure and efficient means of embedding secret data into images while maintaining the appearance of the original image.

## Modules

The Image Steganography System consists of the following modules:

1. **Cover Object (CO):** This module represents the original image in which data hiding will be performed. The CO acts as a carrier for the secret message.

2. **Secret Data (SD):** In this module, the secret message or data to be concealed is provided. The SD is embedded within the CO using steganographic techniques.

3. **Stego Object (SO):** After embedding the secret data into the CO, the resulting image is referred to as the stego object (SO). The SO appears identical to the original CO to the naked eye but contains hidden information.

4. **Stego Key (SK):** The stego key (SK) is used to retrieve the hidden data from the stego object. It contains information necessary for the extraction process.

## Techniques Used

The Image Steganography System employs various steganographic techniques, including:

- **Spatial Domain Embedding:** Directly using pixel values of the cover object to embed secret messages.
- **Transform Domain Embedding:** Transforming the image from spatial to frequency domain using techniques such as Discrete Wavelet Transform (DWT), Discrete Cosine Transform (DCT), Ridgelet Transform, Hadamard Transform, etc., and embedding data in specific transform coefficients.
- **LSB Image Steganography:** Least Significant Bit (LSB) embedding technique, enhanced with encryption technology for improved security and higher Peak Signal-to-Noise Ratio (PSNR).

## Usage

To use the Image Steganography System:

1. Provide the cover object (CO) image in which you want to hide the secret data.
2. Input the secret data (SD) that you wish to conceal within the CO.
3. Execute the embedding process, which will generate the stego object (SO) containing the hidden data.
4. Optionally, provide a stego key (SK) for extracting the hidden data from the stego object.
5. To extract the hidden data, use the stego key (SK) and the stego object (SO) to retrieve the original secret message.

## Support

For any inquiries or issues regarding the Image Steganography System, please contact the development team at steganography_support@example.com.


