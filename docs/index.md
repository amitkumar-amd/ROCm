<head>
  <meta charset="UTF-8">
  <meta name="description" content="AMD ROCm documentation">
  <meta name="keywords" content="documentation, guides, installation, compatibility, support,
  reference, ROCm, AMD, Amit-copy-index-change">
</head>

# AMD ROCm™ documentation

Welcome to the ROCm docs home page! If you're new to ROCm, you can review the following
resources to learn more about our products and what we support:

* [What is ROCm?](./what-is-rocm.md)
* [Release notes](./about/release-notes.md)

You can install ROCm on our Radeon™, Radeon™ PRO, and Instinct™ GPUs. If you're using Radeon
GPUs, we recommend reading the
{doc}`Radeon-specific ROCm documentation<radeon:index>`.

Our documentation is organized into the following categories:

::::{grid} 1 2 2 2
:class-container: rocm-doc-grid

:::{grid-item-card}
:padding: 2
:img-top: ./data/banner-installation.png

* Linux
  * {doc}`Quick-start (Linux)<rocm-install-on-linux:tutorial/quick-start>`
  * {doc}`Linux install guide<rocm-install-on-linux:how-to/native-install/index>`
  * {doc}`Package manager integration<rocm-install-on-linux:how-to/native-install/package-manager-integration>`
* Windows
  * {doc}`Windows install guide<rocm-install-on-windows:how-to/install>`
  * {doc}`Application deployment guidelines<rocm-install-on-windows:conceptual/deployment-guidelines>`
* {doc}`Install Docker containers<rocm-install-on-linux:how-to/docker>`
* {doc}`PyTorch for ROCm<rocm-install-on-linux:how-to/3rd-party/pytorch-install>`
* {doc}`TensorFlow for ROCm<rocm-install-on-linux:how-to/3rd-party/tensorflow-install>`
* {doc}`MAGMA for ROCm<rocm-install-on-linux:how-to/3rd-party/magma-install>`
* {doc}`ROCm & Spack<rocm-install-on-linux:how-to/spack>`
:::

:::{grid-item-card}
:padding: 2
:img-top: ./data/banner-compatibility.png

* {doc}`System requirements (Linux)<rocm-install-on-linux:reference/system-requirements>`
* {doc}`System requirements (Windows)<rocm-install-on-windows:reference/system-requirements>`
* {doc}`Third-party<rocm-install-on-linux:reference/3rd-party-support-matrix>`
* {doc}`User/kernel space<rocm-install-on-linux:reference/user-kernel-space-compat-matrix>`
* {doc}`Docker<rocm-install-on-linux:reference/docker-image-support-matrix>`
* [OpenMP](./about/compatibility/openmp.md)
* {doc}`ROCm on Radeon GPUs<radeon:index>`
:::

:::{grid-item-card}
:padding: 2
:img-top: ./data/banner-reference.png

* [API libraries](./reference/api-libraries.md)
  * Artificial intelligence
  * C++ primitives
  * Communication
  * Fast Fourier transforms
  * HIP
  * Linear algebra
  * Random number generators
* [Tools](./reference/rocm-tools.md)
  * Development
  * Performance analysis
  * System
:::

:::{grid-item-card}
:padding: 2
:img-top: ./data/banner-howto.png

* [System tuning for various architectures](./how-to/tuning-guides.md)
  * [MI100](./how-to/tuning-guides/mi100.md)
  * [MI200](./how-to/tuning-guides/mi200.md)
  * [RDNA2](./how-to/tuning-guides/w6000-v620.md)
* [Setting up for deep learning with ROCm](./how-to/deep-learning-rocm.md)
* [GPU-enabled MPI](./how-to/gpu-enabled-mpi.rst)
* [System level debugging](./how-to/system-debugging.md)
* [GitHub examples](https://github.com/amd/rocm-examples)
:::

:::{grid-item-card}
:padding: 2
:img-top: ./data/banner-conceptual.png

* [GPU architecture](./conceptual/gpu-arch.md)
  * [MI100](./conceptual/gpu-arch/mi100.md)
  * [MI200](./conceptual/gpu-arch/mi200-performance-counters.md)
  * [MI250](./conceptual/gpu-arch/mi250.md)
* [GPU memory](./conceptual/gpu-memory.md)
* [Compiler disambiguation](./conceptual/compiler-disambiguation.md)
* [File structure (Linux FHS)](./conceptual/file-reorg.md)
* [GPU isolation techniques](./conceptual/gpu-isolation.md)
* [LLVM ASan](./conceptual/using-gpu-sanitizer.md)
* [Using CMake](./conceptual/cmake-packages.rst)
* [ROCm & PCIe atomics](./conceptual/More-about-how-ROCm-uses-PCIe-Atomics.rst)
* [Inception v3 with PyTorch](./conceptual/ai-pytorch-inception.md)
* [Inference optimization with MIGraphX](./conceptual/ai-migraphx-optimization.md)
* [OpenMP support in ROCm](./about/compatibility/openmp.md)
:::

::::
