# uPNG -- derived from LodePNG version 20100808
==========================================
 
This project is fork by [there]()

## MODIFY
- 1 add a way to ouput data, so you can decode image data into preallocated buffers.

## TEST

- If you need to deocde a png image and store the raw data into a preallocated buffer, you need use `upng_decode_to_buffer()` fun. Like that `upng_decode_to_buffer(upng, (unsigned char *)decoder_buffer, sizeof(decoder_buffer));`.

- The size of preallocated buffer is must have a minimum size of that png file size plus width\*height\*3. 
