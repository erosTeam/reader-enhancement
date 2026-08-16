# reader-enhancement

Shared HarmonyOS NEXT native library for NextN / NextE reader image processing:
ncnn Vulkan super resolution, MindSpore Lite CUNet upscaling, comic region
detection / text masking / bubble masking / inpainting, and native RGBA image
decode.

Consumed as a HAR through ohpm (file: dependency or private registry). The
NAPI module builds to libreader_enhancement.so.

## Third party

- ncnn (BSD-3-Clause) under src/main/cpp/third_party/ncnn (LICENSE.txt there)
- llvm-openmp runtime notice under src/main/cpp/third_party/llvm-openmp
