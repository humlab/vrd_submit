# Abstract

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/humlab/vrd_submit/main?filepath=tracking-and-tracing-audiovisual-reuse--introducing-the-video-reuse-detector.ipynb)

The reuse and reappropriation of audiovisual content have been a recurring topic of research in the humanities, not least in studies of remix cultures. An open question that remains, however, is how artificial intelligence and machine learning may help scholars study the reuse of audiovisual heritage. In this article, we introduce the Video Reuse Detector (VRD) – a methodological toolkit for identifying visual similarities in audiovisual archives with the help of machine learning. Designed to assist in the study of the “social life” and “cultural biographies” ((Kopytoff 1986), (Appadurai 1986)) of video clips, the VRD helps explore how the meaning of historic footage changes when it circulates and is recycled/cross-referenced in video productions through time. The toolkit uses machine learning techniques (specifically, convolutional neural networks) combined with tools for performing similarity searches (specifically, the Faiss library) to detect copies in audiovisual archives. It also assembles a series of tools for trimming and preparing datasets and filtering/visualizing matching results (such as introducing similarity thresholds, filtering based on sequential matches of frames, and visually viewing the final matching results). Inspired by the “visual turn” in digital history and digital humanities research, the article introduces and exemplifies the basic logic and rationale behind the VRD, and discusses how the digitization of audiovisual archives opens new ways of exploring the reuse of historic moving images. 


# Keywords
Digital methods, Machine learning, Cultural reuse, Video archives


# Licenses
The VRD is applied to two videos that are openly available on Archive.org:

[The Eagle Has Landed: The Flight of Apollo 11](https://archive.org/details/gov.archives.arc.45017) (28 min) released by the U.S. National Aeronautics and Space Administration (NASA) in 1969. Licensed under CC0 1.0 Universal.

[The Moon and Us](https://archive.org/details/journey-through-the-solar-system-episode-06-the-moon-us) (28 min) Episode 6, in the documentary series Journey Through the Solar System released by NASA in 1983. Licensed under Attribution-NonCommercial-NoDerivs 4.0 International.

Before uploading the videos on Github for the VRD demo, we converted them to hvc1 in order to stay within Github's allowed file size of 100 mb/file.

# Code

The source code for the VRD library can be found on [Github](https://github.com/humlab/video_reuse_detector). It is also available for installation using `pip install video-reuse-detector`. 

The PyPI page can be found [here](https://pypi.org/project/video-reuse-detector/).
