###Commands:

Get a list of all the arguments:

    python basecrack.py -h

To decode a single base encoding from user input:

    python basecrack.py

To decode multiple base encodings from a file **(-f/--file)**:

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
    
