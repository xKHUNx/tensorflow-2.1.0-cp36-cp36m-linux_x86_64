# Tensorflow 2.1.0 Ubuntu 18.04 GPU (Compute 5.0), Python 3.6.9, CUDA 10.2, no AVX (-march=nehalem)
Copied from: https://github.com/yaroslavvb/tensorflow-community-wheels/issues/153

# Original download link
https://drive.google.com/file/d/1Lzfi3mNljv31cZD3R_D2m_dPMMBSkyGk/view?usp=sharing

# Version Issue
dstarcev commented on May 12
> ```
> import tensorflow as tf
> 
> print(tf.__version__)
> ```
> 
> 
> outputs 2.1.0, but it works on my celeron

buckohfive (Original uploader) commented on May 12
> Updated title. Interestingly enough, this was built with the latest stable release from github.com, which states it is 2.2.0. I git clone'd from github on 8 May. Maybe its returning the wrong version?

