# PRODIGY_CS_02

# Image Encryption and Decryption

This Python script performs encryption and decryption of images using the XOR operation with a key. It uses the Python Imaging Library (PIL) to manipulate images.

## Usage

 1.Ensure you have Python installed on your system.
 2.Install the required dependencies listed in the requirements.txt file using pip install -r requirements.txt.
 3.Run the image_encrypt_decrypt.py script.
 4.The script will encrypt an input image using the provided key and save the encrypted image.
 5.It will then decrypt the encrypted image using the same key and save the decrypted image.
 6.Check the output images to verify the encryption and decryption process.

## Functions

encrypt_image(input_image, key, output_image): Encrypts the input image using XOR operation with the provided key and saves the encrypted image.
decrypt_image(input_image, key, output_image): Decrypts the input image using XOR operation with the same key and saves the decrypted image.

## Example
if __name__ == "__main__":
  encrypt_image("original.png", 123, "encrypted.png")
  decrypt_image("encrypted.png", 123, "decrypted.png")

  print("Encryption and decryption completed successfully!")
