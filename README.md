# MacOS-GPU-ML

Using Tensorflow or PyTorch on MacOS with GPU support is a complicated affair. At present all these frameworks only support GPU acceleration based on NVIDIA GPU chips and CUDA. But, unfortunatelly in the last 10 years or so, Apple has stopped shipping computers (desktops or laptops) using NVIDIA chips. That means there is very litle incentive to update the support. As a result all framworks are provided out of the box with GPU support only for Linux and Windows.

The good news is that things work on a MacOS. It's just a little bit more work to have it setup and you need to keep in mind the dependencies when updating your Apple machine in the future.

One of the nice developement in the last year or so, with the introduction of Thunderbolt 3 in the new MacBook models, is the support for eGPUs: external enclosures that host a GPU card and can be used by a MacBook by connecting it with a Thuderbolt 3 cable. This is made possible by the fact that Thunderbolt 3 permits data transfers of up to 40Gb/s, eGPU thus being one of the main beneficiaries of this performance. As an added benefit, the Thunderbolt 3 doubles up as a power cable, supporting up to 100W of power distribution along the 40Gb/s data traffic. Many eGPU enclosures support power delivery making it very convenient to connect them to a MacBook: just plug one of these cables between the enclosure and the laptop and that is all you need!

