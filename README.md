# InterSpeech 2020

We published 4 papers in Interspeech 2020, the papers are as followings.

**The JD AI Speaker Verification System for the FFSVC 2020 Challenge**

Ying Tong(JD AI Research), Wei Xue(JD AI Research), Shanluo Huang(JD AI Research), Lu Fan(JD AI Research), Chao Zhang(JD AI Research), Guohong Ding(JD AI Research) and Xiaodong He(JD AI Research)

Abstract: This paper presents the development of our systems for the Interspeech 2020 Far-Field Speaker Verification Challenge (FFSVC). Our focus is the task 2 of the challenge, which is to perform far-field text-independent speaker verification using a single microphone array. The FFSVC training set provided by the challenge is augmented by pre-processing the far-field data with both beamforming, voice channel switching, and a combination of weighted prediction error (WPE) and beamforming. Two open-access corpora, CHData in Mandarin and VoxCeleb2 in English, are augmented using multiple methods and mixed with the augmented FFSVC data to form the final training data. Four different model structures are used to model speaker characteristics: ResNet, extended time-delay neural network (ETDNN), Transformer, and factorized TDNN (FTDNN), whose output values are pooled across time using the self-attentive structure, the statistic pooling structure, and the GVLAD structure. The final results are derived by fusing the adaptively normalized scores of the four systems with a two-stage fusion method, which achieves a minimum of the detection cost function (minDCF) of 0.3407 and an equal error rate (EER) of 2.67% on the development set of the challenge.


**Efficient WaveGlow: An Improved WaveGlow Vocoder with Enhanced Speed**

Wei Song(JD AI Research), Guanghui Xu(JD AI Research), Zhengchen Zhang(JD.com), Chao Zhang(University of Cambridge), Xiaodong He(JD AI Research) and Bowen Zhou(JD AI Research)

Abstract: Neural vocoder, such as WaveGlow, has become an important component in recent high-quality text-to-speech (TTS) systems. In this paper, we propose Efficient WaveGlow (EWG), a flow-based generative model serving as an efficient neural vocoder. Similar to WaveGlow, EWG has a normalizing flow backbone where each flow step consists of an affine coupling layer and an invertible 1x1 convolution. To reduce the number of model parameters and enhance the speed without sacrificing the quality of the synthesized speech, EWG improves WaveGlow in three aspects. First, the WaveNet-style transform network in WaveGlow is replaced with an FFTNet-style dilated convolution network. Next, to reduce the computation cost, group convolution is applied to both audio and local condition features. At last, the local condition is shared among the transform network layers in each coupling layer. As a result, EWG can reduce the number of floating-point operations (FLOPs) required to generate one-second audio and the number of model parameters both by more than 12 times. Experimental results show that EWG can reduce real-world inference time cost by more than twice, without any obvious reduction in the speech quality.

Audio samples of this paper can be found at [Efficient WaveGlow Audio Samples](http://weixsong.github.io/demos/EfficientWaveGlow/index.html).


