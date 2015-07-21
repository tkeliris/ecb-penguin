# ecb-penguin
ECB TUX penguin with AES-ECB

This implementation only works with BMP images that have certain characteristics. The main characteristic that an image must have for this solution to work is that it has to be of a size that's multiple of 16 bytes (for the encryption part, AES ECB operates on 16 byte chunks). Feel free to improve this to accept more image formats and pad to 16 byte multiples :)

If you don't provide an image, an appropriate image from the web is automatically downloaded.

im_show from Image is known to cause problems on some platforms. I tested this on an Ubuntu 14.10 distro with Python 2.7.

You can check out the related [stackoverflow answer](http://stackoverflow.com/questions/29039773/produce-the-ecb-penguin-with-aes-in-python), feel free to upvote it if
it helped you!
