## Pixel Manipulation for Image Encryption<br>
A simple Python project that demonstrates image encryption and decryption by manipulating pixel RGB values using a symmetric key. The tool allows users to encrypt an image by altering pixel values and then decrypt it using the same key.

## How It Works<br>
The encryption and decryption process modifies the Red, Green, and Blue (RGB) values of each pixel using a user-provided integer key:

# Encryption<br>
Encrypted_value = (Original_value + key) % 256

# Decryption<br>
Decrypted_value = (Encrypted_value - key) % 256<br>
This ensures the image can be perfectly recovered if the same key is used.

# Features<br>
Encrypts any image by modifying RGB pixel values.

Decrypts the encrypted image using the same key.

Displays both original/encrypted/decrypted images.

Command-line interface with user-friendly prompts.

Supports .png, .jpg, and other image formats supported by Pillow.

**Requirements**<br>
Python 3.x

Pillow library

**Install dependencies with:**<br>
pip install Pillow

**How to Run**<br>
Clone this repository:<br>
git clone https://github.com/your-username/image-encryption-tool.git<br>
cd image-encryption-tool

**Run the program:**<br>
python Pixel_Manipulation.py

**Follow the terminal prompts to:**

Choose to encrypt or decrypt

Enter file paths and key

View the resulting images

**License**<br>
This project is licensed under the MIT License.<br>
Feel free to use, modify, and share it!

**Author**
Gagan V B
https://github.com/Gaganvb04