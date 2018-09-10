# Swift Tutorials

This repository contains Jupyter notebooks demonstrating TensorFlow in Swift.

# How to run

## Docker

1. `docker run -t -i -p 8888:8888 --cap-add SYS_PTRACE gcr.io/swift-tensorflow/jupyter`
2. It should print out a URL. Open it in your browser. You may have to fix up
   the URL by replacing `(xxxxxxxxxxx or 127.0.0.1)` with `127.0.0.1`.
3. In Jupyter, navigate to `swift-tutorials/iris/swift_tensorflow_tutorial.ipynb`.

If you are curious, the [Dockerfile is in the swift-jupyter
repository](https://github.com/google/swift-jupyter/tree/master/docker).

## Manual installation

### Requirements

* macOS 10.13.5 or later, with Xcode 10.0 beta or later; OR
* Ubuntu 16.04 (64-bit); OR
* other operating systems may work, but you will have to build Swift from
  sources.

### Installation

Install the swift-jupyter kernel by following the "Installation Instructions
With TensorFlow toolchain" in the
[swift-jupyter readme](https://github.com/google/swift-jupyter). The tutorial requires the 2018-09-09 toolchain, or later.

### Running

Put this repository in the directory where you run `jupyter notebook`, and then
open `iris/swift_tensorflow_tutorial.ipynb` in Jupyter.
