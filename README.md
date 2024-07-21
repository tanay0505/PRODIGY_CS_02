# PRODIGY_CS_02


This repository contains a Python script that will encrypt/decrypt an image using simple mathematical logic. It requires two things, data and key.When XOR operation is applied on both the operands i.e data and key, the data gets encrypted but when the same process is done again with the same key-value data gets decrypted.

<br>

Features:-
- Encrypt Images: Apply a key to modify pixel values and encrypt the image.
- Decrypt Images: Reverse the encryption by using the same key to restore the original image.

<br>

Encryption:-
First, we will select an image, and then we will convert that image into a byte array due to which the image data will be totally converted into numeric form, and then we can easily apply the XOR operation to it. Now, whenever we will apply the XOR function on each value of the byte array then the data will be changed due to which we will be unable to access it. But we should remember one thing here our encryption key plays a very important role without that key we can not decrypt our image. It acts as a password to decrypt it.

<br>

Decryption:-
It is nothing but a process of converting our encrypted data into a readable form. Here we will again apply the same XOR operation on an encrypted image to decrypt it. But always remember that our encryption key and decryption key must be the same.
