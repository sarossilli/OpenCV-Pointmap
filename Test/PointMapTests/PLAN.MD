## Python quick start

Pre-built pip and conda packages support Ubuntu 18.04+, macOS 10.15+ and
Windows 10 (64-bit) with Python 3.6-3.9.

```bash
# Install Open3D stable release with pip (including in conda virtual environments)
$ pip install open3d

# Test the installation
$ python -c "import open3d as o3d; print(o3d)"

```

To get the latest features in Open3D, install the
[development pip package](http://www.open3d.org/docs/latest/getting_started.html#development-version-pip).
To compile Open3D from source, refer to
[compiling from source](http://www.open3d.org/docs/release/compilation.html).


Open3D-ML is an extension of Open3D for 3D machine learning tasks. It builds on
top of the Open3D core library and extends it with machine learning tools for
3D data processing. To try it out, install Open3D with PyTorch or TensorFlow and check out