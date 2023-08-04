# Before anything else
To install required modules (`pycryptodome` and `Pillow`), you can do one of the following
1. `pip install -r requirements.txt`.
2. if you use a conda virtual environemnt, run `conda install --file requirements.txt`

# Challenge 1: decrypting the two encrypted images
You will need `pycryptodome` for this.

Decrypt `encrypted_image1` using `key1.bin` and `encrypted_image2` using `key2.bin`. Remember they use different methods of encryption. Store the decrypted images in two files: `decrypted_image1.jpeg` and `decrypted_image2.jpeg`

# Challenge 2: combining the two decrypted images
You will need `Pillow.Image` for this. 

Use the files `decrypted_image1.jpeg` and `decrypted_image2.jpeg` from the Challenge 1 to generate the final image: `flag.jpeg`. Within `flag.jpeg` you will see the flag's text and then you are finished.