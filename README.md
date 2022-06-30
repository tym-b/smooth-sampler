# Smooth sampler

A drop-in replacement for Pytorch's [grid_sample](https://pytorch.org/docs/stable/generated/torch.nn.functional.grid_sample.html) supporting smoothstep activation for interpolation weights proposed in [Instant NGP](https://nvlabs.github.io/instant-ngp/) by Müller et al. as well as double backpropagation. Currently supports 3D inputs and trilinear interpolation mode. Based on Pytorch's native grid_sampler code.
