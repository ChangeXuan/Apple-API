# VideoTOolbox
### Work directly with hardware-accelerated video encoding and decoding capabilities.
## 概述
VideoToolbox is a low-level framework that provides direct access to hardware encoders and decoders. It provides services for video compression and decompression, and for conversion between raster image formats stored in CoreVideo pixel buffers. These services are provided in the form of session objects (compression, decompression, and pixel transfer), which are vended as Core Foundation (CF) types. Apps that don't need direct access to hardware encoders and decoders should not need to use VideoToolbox directly.
