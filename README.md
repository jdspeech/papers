# InterSpeech 2020

We published 4 papers in Interspeech 2020, the papers are as followings.

**Efficient WaveGlow: An Improved WaveGlow Vocoder with Enhanced Speed**

Wei Song(JD AI Research), Guanghui Xu(JD AI Research), Zhengchen Zhang(JD.com), Chao Zhang(University of Cambridge), Xiaodong He(JD AI Research) and Bowen Zhou(JD AI Research)

Abstract: Neural vocoder, such as WaveGlow, has become an important component in recent high-quality text-to-speech (TTS) systems. In this paper, we propose Efficient WaveGlow (EWG), a flow-based generative model serving as an efficient neural vocoder. Similar to WaveGlow, EWG has a normalizing flow backbone where each flow step consists of an affine coupling layer and an invertible 1x1 convolution. To reduce the number of model parameters and enhance the speed without sacrificing the quality of the synthesized speech, EWG improves WaveGlow in three aspects. First, the WaveNet-style transform network in WaveGlow is replaced with an FFTNet-style dilated convolution network. Next, to reduce the computation cost, group convolution is applied to both audio and local condition features. At last, the local condition is shared among the transform network layers in each coupling layer. As a result, EWG can reduce the number of floating-point operations (FLOPs) required to generate one-second audio and the number of model parameters both by more than 12 times. Experimental results show that EWG can reduce real-world inference time cost by more than twice, without any obvious reduction in the speech quality.

Audio samples of this paper can be found at [Efficient WaveGlow Audio Samples](http://weixsong.github.io/demos/EfficientWaveGlow/index.html).


