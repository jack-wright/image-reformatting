# Image Reformatting

This is a small script that runs through any images stored in a stated directory, uses the tinypng api to compress the original images, creates resized versions for mobile, and then Webp versions of both the original and mobile images.

Included is an ```.env.example``` file. Inside here are two environment variables called ```IMAGE_DIRECTORY``` and ```TINYPNG_KEY```. ___You will need to register for an api key with Tinypng to be able to use this script.___