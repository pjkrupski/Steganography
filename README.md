# Steganography
Project allows for hiding encrypted messages within pictures


The goal of this project is to combine concepts from Computer Vision, Digital Imagery, and Cyber Security 
to create a system that will allow for an encrypted message to be hidden inside a jpg picture.


The Process,

First, a message will be entered that the user wants to encrypt. This message will be taken in
and run against a simple ceaser cipher that will assign numbers to letters based on a pre existing
formula. This string of numbers will now be the input for the picture encryption utility.


The three fundamental parts of any encryption is data, the key, and the encryption mechanism.
Since after running the ceaser cipher the program will now have the data, the next step is
to generate the key. By leveraging a random number generator, a key will be generated that
can be used to determine where in the 3d array each character of the message is stored and
in what order it will need to be in for reconstruction. The encryption mechanism 
is the steganography process, see [Steganograph](https://www.comptia.org/blog/what-is-steganography#:~:text=Steganography%20is%20the%20practice%20of%20hiding%20a%20secret%20message%20inside,something%20that%20is%20not%20secret.&text=These%20days%2C%20many%20examples%20of,a%20Word%20or%20Excel%20document)for reference 

