Pix2Pix
=======

![screenshot](https://i.imgur.com/xjzPABb.gif)
![screenshot](https://i.imgur.com/wnR1jmCm.jpg)

This is a real-time [pix2pix] (image-to-image translation with deep neural
network) implementation with Unity. This contains its own implementation of
inference engine, so it doesn't require installation of other neural network
frameworks.

[pix2pix]: https://github.com/phillipi/pix2pix

Sketch Pad Demo
---------------

Sketch Pad is a demonstration that resembles the famous [edges2cats] demo but
in real time. You can download a pre-built binary from the [Releases] page.

[Video](https://vimeo.com/)

[edges2cats]: https://affinelayer.com/pixsrv/
[Releases]: https://github.com/keijiro/Pix2Pix/releases

System requrements
------------------

- Unity 2018.1
- Compute shader capability (DX11, Metal, Vulkan, etc.)

Although it's implemented in a platform agnostic fashion, many parts of that
are optimized for NVIDIA GPU architectures. To run the Sketch Pad demo
flawlessly, it's highly recomended to use GeForce GTX 1070 or greater.

Use Other Models
----------------

This implementation supports the weight data format used in Christopher Hesse's
[interactive demo]. Pick one of the [pre-trained models], or you can train your
own model with using [pix2pix-tensorflow].

[interactive demo]: https://affinelayer.com/pixsrv/
[pre-trained models]: https://github.com/affinelayer/pix2pix-tensorflow-models
[pix2pix-tensorflow]: https://github.com/affinelayer/pix2pix-tensorflow
