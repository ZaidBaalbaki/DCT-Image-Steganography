# DCT Image Steganography
### This project is for the project #17 (Stegonography(Image and Text)) for the course EECE 455 at AUB Spring 2022
To run this project you need Python 3 and the following Python libraries:
- OpenCV (cv2): pip install opencv-python
- bitstring: pip install bitstring
- Numpy: pip install numpy
- Zigzag (already in the project folder)
    "zigzag.py" location source: https://github.com/amzhang1/simple-JPEG-compression/blob/master/zigzag.py

In order to imbed hidden text in an image use the file 'run_stego_algorithim.py' as follows:
1. Open the file with a text editor
2. Input the file path of your PNG image in the ```COVER_IMAGE_FILEPATH``` variable
3. Input the output file path of your PNG image in the ```STEGO_IMAGE_FILEPATH```variable
4. Input your secret message in the variable ```SECRET_MESSAGE_STRING``` as a string
5. Run the file from cmd using: `python run_stego_algorithim.py`

In order to extract the hidden text from the image,
run the file 'extract_stego_image.py'
use: `python extract_stego_image.py`
