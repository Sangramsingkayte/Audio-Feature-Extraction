# # Audio Feature Extraction
The repository describes the feature extraction methods for Audio signals.

## Free speech datasets
* [OpenLSR](http://www.openslr.org): OpenSLR is a site devoted to hosting speech and language resources, such as training corpora for speech recognition, and software related to speech recognition.
* [VoxForge](http://www.voxforge.org/): VoxForge is now mirroring the LT and the Teleccoperation group Open Speech Data Corpus for German with 35 hours of speech from about 180 speakers. 
* [TIMIT](https://catalog.ldc.upenn.edu/ldc93s1): The DARPA TIMIT Acoustic-Phonetic Continuous Speech Corpus.
* [Mozilla Speech](https://medium.com/mozilla-open-innovation/sharing-our-common-voice-mozilla-releases-second-largest-public-voice-data-set-e88f7d6b7666): Mozilla Releases the world's Second Largest Public Voice Data Set on Nov 29th, 2017.
* [Open Data for Deep Learning](https://deeplearning4j.org/opendata)

## File description
* feature_extraction_functions.py: a set of feature extraction functions from [RDShi-SpeakerCount](https://github.com/RDShi/SpeakerCount).
* MFCC: Mel-frequency cepstral coefficients calculation.
  * MFCC.py, MFCCTest.py: Compute the MFCC feature.
  * FeatureExtraction.ipynb: Speech preprocessing, including loading data, pre-emphasis, framing, window, Fourier-transform, power spectrum, filter banks, mfccs and mean normalization.
* Volume: volume calculation.<br>
![](/Volume/VolumeTest.png)
* ZeroCR: Zero-Crossing Rate calculation.<br>
![](/ZeroCR/ZeroCR.png)
* Pitch: Pitch calculation and pitch tracking.<br>
![](/Pitch/pitch.png)
![](/Pitch/pitchTrack.png)
* Timbre: spectrogram drawing.<br>
![](/Timbre/spectrogram.png)
* VAD: EPD (End-Point Detection), or Speech Detection, or VAD(Voice Activity Detection).<br>
![](/VAD/VAD01.png)
![](/VAD/VAD02.png)

## Requirements
[Anaconda](https://www.anaconda.com/) (Python)

## References
* http://haythamfayek.com/2016/04/21/speech-processing-for-machine-learning.html
* https://github.com/wiseman/py-webrtcvad
* https://github.com/jameslyons/python_speech_features
* https://github.com/ZhihaoDU/speech_feature_extractor
* http://ibillxia.github.io/blog/archives/
* http://stevemorphet.weebly.com/speech-and-audio-processing
* MFCC
  * http://blog.csdn.net/zouxy09/article/details/9156785
  * http://blog.csdn.net/xmdxcsj/article/details/51228791
  * http://practicalcryptography.com/miscellaneous/machine-learning/guide-mel-frequency-cepstral-coefficients-mfccs/
* Git tutorial
  * https://jingyan.baidu.com/article/2fb0ba4091a21c00f2ec5fbf.html
  * https://jingyan.baidu.com/article/fec4bce2285b56f2618d8bdc.html


