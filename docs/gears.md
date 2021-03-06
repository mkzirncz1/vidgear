<!--
===============================================
vidgear library source-code is deployed under the Apache 2.0 License:

Copyright (c) 2019-2020 Abhishek Thakur(@abhiTronix) <abhi.una12@gmail.com>

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
===============================================
-->

# Introduction

## Gears, What are these?

<p align="center">
  <img src="../assets/images/gears_fbd.png" alt="@Vidgear Functional Block Diagram"/>
</p>


VidGear is built with Gears(APIs), each with some unique functionality. These Gears provides VidGear, a powerful, easy-to-use, highly extensible, **Multi-Threaded + Asyncio** layer above many state-of-the-art specialized libraries to exploit their internal properties flexibly, while providing robust error-free and unparalleled real-time performance.


&nbsp;

## Gears Classification

These Gears can be classified as follows:

### A. VideoCapture Gears

> **Basic Function:** Reading [`numpy.ndarray`](https://numpy.org/doc/1.18/reference/generated/numpy.ndarray.html#numpy-ndarray) frames.

**VideoCapture Gears**

* [CamGear](../gears/camgear/overview/): Multi-threaded API targeting various IP-USB-Cameras/Network-Streams/YouTube-Video-URLs.
* [PiGear](../gears/pigear/overview/): Multi-threaded API targeting  various Raspberry Pi Camera Modules.
* [ScreenGear](../gears/screengear/overview/): Multi-threaded ultra-fast Screencasting.    
* [VideoGear](../gears/videogear/overview/): Common API with internal [Video Stabilizer](../gears/stabilizer/overview/) wrapper.  

### B. VideoWriter Gears

> **Basic Function:** Writing [`numpy.ndarray`](https://numpy.org/doc/1.18/reference/generated/numpy.ndarray.html#numpy-ndarray) frames to a video file.

* [WriteGear](../gears/writegear/introduction/): Handles Flexible Lossless Video Encoding and Compression.

### C. Network Gears

> **Basic Function:** Sending/Receiving [`numpy.ndarray`](https://numpy.org/doc/1.18/reference/generated/numpy.ndarray.html#numpy-ndarray) frames over the network.

* [NetGear](../gears/netgear/overview/): Handles high-performance video-frames & data transfer between interconnecting systems over the network.

* **Asynchronous I/O Network Gears:**

    * [WebGear](../gears/webgear/overview/): ASGI Video Server that can send live video-frames to any web browser on the network.
    * [NetGear_Async](../gears/netgear_async/overview/): Immensely Memory-efficient Asyncio video-frames network messaging framework.

&nbsp;