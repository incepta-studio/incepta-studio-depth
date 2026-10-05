incepta_studio by Incepta Studios
Independent project. Powered by Video Depth Anything.

# incepta_studio 0.1.4 — third-party software

The Incepta interface and integration are separate from the underlying model and runtime components. This is not an official DepthAnything or ByteDance product.

Video Depth Anything Small: Apache-2.0. Source: https://github.com/DepthAnything/Video-Depth-Anything . Model: https://huggingface.co/depth-anything/Video-Depth-Anything-Small . Upstream license and source headers are preserved in resources/inference/vendor. Local changes add PyTorch SDPA attention and Windows export compatibility.

Python: PSF license, included in resources/inference/python/LICENSE.txt.

PyTorch 2.6.0+cu126 and torchvision 0.21.0+cu126, including their CUDA runtime dependencies: original LICENSE and NOTICE files are included in their .dist-info directories under resources/inference/python/Lib/site-packages. No NVIDIA driver is included.

NumPy, OpenCV, Pillow, Matplotlib, imageio, imageio-ffmpeg, einops, tqdm and the remaining Python dependencies: original distribution license files are preserved in the corresponding .dist-info directories.

FFmpeg 7.1 essentials by gyan.dev is invoked as a separate executable via imageio-ffmpeg. The executable reports --enable-gpl --enable-version3 and is GPLv3 software. The GPLv3 license is included as FFmpeg-COPYING.GPLv3.txt. Build provider and source information: https://www.gyan.dev/ffmpeg/builds/ . FFmpeg 7.1 source: https://github.com/FFmpeg/FFmpeg/tree/n7.1 . Imageio packaging source: https://github.com/imageio/imageio-ffmpeg/tree/v0.6.0 . No FFmpeg source modifications are made by this application.

Electron 44.5.1 / Chromium: license files LICENSE.electron.txt and LICENSES.chromium.html are installed beside the application executable.

Do not remove upstream notices when redistributing this application. This local installer is an unsigned development build, not a signed public release.
