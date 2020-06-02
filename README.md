# cuda-ffmpeg-opencv-docker
[![Docker Cloud Automated build](https://img.shields.io/docker/cloud/automated/tigerdockermediocore/cuda-ffmpeg-opencv-docker)](https://hub.docker.com/r/tigerdockermediocore/cuda-ffmpeg-opencv-docker)
[![Docker Cloud Build Status](https://img.shields.io/docker/cloud/build/tigerdockermediocore/cuda-ffmpeg-opencv-docker)](https://hub.docker.com/r/tigerdockermediocore/cuda-ffmpeg-opencv-docker)

OpenCV docker with CUDA and FFMPEG support as devel image.
The base images are from NVIDIA NGC (nvcr.io) to support server-level GPUs.
It will warn if your GPUs are not servel level (e.g. V100), but it will just work fine.

Mostly brought from [jrottenberg/ffmpeg](https://github.com/jrottenberg/ffmpeg), and [Borda/docker_python-opencv-ffmpeg](https://github.com/Borda/docker_python-opencv-ffmpeg)

## Contains

 - Cuda + CuDNN
 - ffmpeg with cuda support
 - OpenCV with CUDA and FFMPEG support

## Libraries in FFMPEG

- [FFMPEG_VERSION](http://ffmpeg.org/releases/): [GNU Lesser General Public License (LGPL) version 2.1](https://ffmpeg.org/legal.html)
- [OGG_VERSION](https://xiph.org/downloads/): [BSD-style license](https://git.xiph.org/?p=mirrors/ogg.git;a=blob_plain;f=COPYING;hb=HEAD)
- [OPENCOREAMR_VERSION](https://sourceforge.net/projects/opencore-amr/files/opencore-amr/): [Apache License](https://sourceforge.net/p/opencore-amr/code/ci/master/tree/LICENSE)
- [VORBIS_VERSION](https://xiph.org/downloads/): [BSD-style license](https://git.xiph.org/?p=mirrors/vorbis.git;a=blob_plain;f=COPYING;hb=HEAD)
- [THEORA_VERSION](https://xiph.org/downloads/): [BSD-style license](https://git.xiph.org/?p=mirrors/theora.git;a=blob_plain;f=COPYING;hb=HEAD)
- [LAME_VERSION](http://lame.sourceforge.net/download.php): [GNU Lesser General Public License (LGPL) version 2.1](http://lame.cvs.sourceforge.net/viewvc/lame/lame/LICENSE?revision=1.9)
- [OPUS_VERSION](https://www.opus-codec.org/downloads/): [BSD-style license](https://www.opus-codec.org/license/)
- [VPX_VERSION](https://github.com/webmproject/libvpx/releases): [BSD-style license](https://github.com/webmproject/libvpx/blob/master/LICENSE)
- [WEBP_VERSION](https://storage.googleapis.com/downloads.webmproject.org/releases/webp/index.html): [BSD-style license](https://github.com/webmproject/libvpx/blob/master/LICENSE)
- [XVID_VERSION](https://labs.xvid.com/source/): [GNU General Public Licence (GPL) version 2](http://websvn.xvid.org/cvs/viewvc.cgi/trunk/xvidcore/LICENSE?revision=851)
- [FDKAAC_VERSION](https://github.com/mstorsjo/fdk-aac/releases): [Liberal but not a license of patented technologies](https://github.com/mstorsjo/fdk-aac/blob/master/NOTICE)
- [FREETYPE_VERSION](http://download.savannah.gnu.org/releases/freetype/): [GNU General Public License (GPL) version 2](https://www.freetype.org/license.html)
- [LIBVIDSTAB_VERSION](https://github.com/georgmartius/vid.stab/releases): [GNU General Public License (GPL) version 2](https://github.com/georgmartius/vid.stab/blob/master/LICENSE)
- [LIBFRIDIBI_VERSION](https://www.fribidi.org/): [GNU General Public License (GPL) version 2](https://cgit.freedesktop.org/fribidi/fribidi/plain/COPYING)
- [X264_VERSION](http://www.videolan.org/developers/x264.html): [GNU General Public License (GPL) version 2](https://git.videolan.org/?p=x264.git;a=blob_plain;f=COPYING;hb=HEAD)
- [X265_VERSION](https://bitbucket.org/multicoreware/x265/downloads/): [GNU General Public License (GPL) version 2](https://bitbucket.org/multicoreware/x265/raw/f8ae7afc1f61ed0db3b2f23f5d581706fe6ed677/COPYING)
- [LIBZMQ_VERSION](https://github.com/zeromq/libzmq/releases/): [GNU Lesser General Public License (LGPL) version 3.0](https://github.com/zeromq/libzmq/blob/v4.3.2/COPYING.LESSER)
- [LIBSRT_VERSION](https://github.com/Haivision/srt/releases/): [MPL-2.0](https://github.com/Haivision/srt/blob/master/LICENSE)
