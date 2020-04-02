# Denoising

Given a noisy input image and a target which is not noisy, the encoder in this process can learn how to extract important features and decoder can learn how to produce non noisy construction.

A deeper network will be able to extract more features and recognize patterns.

# Upsampling 

Encoder architecture remains the same. On the decoder side, combine nearest neighbour interpolation with normal convolution. Convolutional layers increase the depth of the unit being processed. Interpolation is done to upsample.
