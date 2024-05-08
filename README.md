# Base Crack System: A Powerful Tool for Decoding Multiple Base Encodings

### Introduction

BaseCrackSystem is a comprehensive Python library designed to empower you to decode a wide range of alphanumeric base encoding schemes with ease. Whether you're a security professional, a data analyst, or simply someone who encounters encoded data, BaseCrackSystem equips you with the tools to efficiently unveil the hidden information within.

# Key Features

### Extensive Base Encoding Support:
Handles a vast array of encoding schemes, including common ones like Base16, Base32, Base64, Base91, Base92 and Base100, as well as less common ones like Base85 and Ascii85.
### Multi-Encoding Decoding:
Decodes data that has been encoded with multiple layers of different base encodings. No need to manually decode each layer separately.
### Image-Based Base Detection:
Integrates with Optical Character Recognition (OCR) to decode bases embedded within images as text.
### EXIF Data Decoding:
Extracts and decodes bases hidden within the Exif metadata of images.
### User-Friendly API:
Offers a well-designed and intuitive API, making it easy for developers to integrate BaseCrackSystem into their projects.
### Command-Line Interface:
Provides a convenient command-line interface (CLI) for users who prefer a direct and non-programmatic way to interact with the library.


### Commands to Run:

**Get a list of all the arguments:**

    python basecrack.py -h

**To decode a single base encoding from user input:**

    python basecrack.py

**To decode multiple base encodings from a file **(-f/--file)**:**

    python basecrack.py -f file.txt

**Magic Mode:** To decode multi-encoded base of any pattern **(-m/--magic)**:

    python basecrack.py --magic

To input an image for **EXIF/OCR** detection mode **(-i/--image)**:

    python3 basecrack.py -i image.jpg (--exif/--ocr)

**EXIF Data:** To decode bases in image EXIF data **(-e/--exif)**:

    python basecrack.py -i image.jpg --exif

**OCR Base Detection:** To decode bases on image with OCR detection **(-c/--ocr)**:

    python basecrack.py -i image.jpg --ocr

To generate a wordlist/output with the decoded bases **(-o/--output)**:

    python basecrack.py -f file.txt -o output-wordlist.txt
    
