# Secret

Simple project to encrypt your super secret data into an image using steganography and pretty simple cyphering. 

# License

[MIT](https://opensource.org/license/mit)

# Dependencies

Project has only one external dependency to work with images: Pillow.

# Running application

Run encoding and decoding as simple as:

    $> ./secret encode my_image.png "my_super_password" "great secret to be encrypted"
    $> ./secret encode my_image.png "my_super_password" path_to_file_tobe_encrypted

    $> ./secret decode my_image_with_secrte.png "my_super_password"
    $> ./secret decode my_image_with_secrte.png "my_super_password" out_fule_name

