# Quickdraw-GAN

The data folder contains the .bin file, which is a raw file will 100 000+ sketches in vector format. bin-file-to-raster.ipynb will make that into an hdf5 of 28x28 bitmaps, but it will be several GB. I never used this approach.

The easier option is to download the .npy files (not included here because of Github's file size limits) [directly from Google](https://console.cloud.google.com/storage/browser/quickdraw_dataset/full/numpy_bitmap/).

The rest should be self explanatory, but I haven't worked with this code in a while. Shout if something makes no sense!
