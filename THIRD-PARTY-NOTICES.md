# Third-party components

Hulumhej connects to your own installation of Stash. SteamVR and FlatVR are installed separately through Steam.

- `Install HH.cmd` downloads original Windows archives from [FFmpeg Builds](https://github.com/FFmpeg-Builds/FFmpeg-Builds), [VideoLAN](https://download.videolan.org/videolan/vlc/3.0.24/), and [MSYS2](https://www.msys2.org/license/). Exact versions and checksums are in `deps-manifest.json`. Installed library notices are under `licenses/`.
- The Native 3D runtime contains [Python 3.12](https://www.python.org/psf/license/), [NumPy 2.3.5](https://github.com/numpy/numpy/tree/v2.3.5), [ONNX Runtime DirectML 1.24.4](https://pypi.org/project/onnxruntime-directml/1.24.4/) and Microsoft Visual C++ runtime files. Python and NumPy notices are in `depth-python/`. The ONNX Runtime notices are in `licenses/`.
- Native 3D uses [Depth Anything V2 Small](https://github.com/DepthAnything/Depth-Anything-V2), by the Depth Anything authors, under the Apache License 2.0. The [ONNX export](https://huggingface.co/onnx-community/depth-anything-v2-small) is pinned to revision `4472b7362082ad9968fee890ca0f1e5aca36b93d`.
- The six geometric sculptures in this package were created for the Hulumhej demo. The separate video credits identify its nature and space footage.
