# PIPpackage
Pedagogical Image Processing Package

This repository was created to build a collection of image procesing functions for small, pixel-level understandable package.
The main purpose is to exemplify how the different filters and algorithms work with clear code that produces small images that can be analysed pixel by pixel.
The use of the algorithms with bigger images might be very slow and inadequate.
Anyway, the discussion and comparison of different implementations is also welcome. Unfortunately, since we are using Python, everything is potentially very slow.
But some algorithms are quite slower than others...

Enjoy and contribute if you feel that you want.

### Available functions

**genImage** - generates an image

**imagePad** - image padding

**printImg** - prints the pixels values of an image

**printImgFloat** - same as above for floating point pixels

**imgConv** - image convolution with a kernel

**sepFilter** - image filtering with a separable filter

**bilinear** - bilinear interpolation of pixel values

**interp** - linear interpolation between two values

**medianHybrid5x5** - 5x5 hybrid median filter

**eqHist** - histogram based image equalization

**dilation** - image dilation with kernel

**erosion** - image erosin with kernel

**hitAndMiss** - Hit & Miss filter

**multiSeg** - Multi class segmentation

**binSeg** - binary image segmentation
