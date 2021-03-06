# InterSpeech 2020

We published 4 papers in Interspeech 2020, the papers are as followings.

**Sound Event Localization and Detection Based on Multiple DOA Beamforming and Multi-task Learning**

Wei Xue(JD AI Research), Ying Tong(JD AI Research), Chao Zhang(JD AI Research), Guohong Ding(JD AI Research), Xiaodong He(JD AI Research) and Bowen Zhou(JD AI Research)

Abstract: The performance of sound event localization and detection (SELD) degrades in source-overlapping cases since features of different sources collapse with each other, and the network tends to fail to learn to separate these features effectively. In this paper, by leveraging the conventional microphone array signal processing to generate comprehensive representations for SELD, we propose a new SELD method based on multiple direction of arrival (DOA) beamforming and multi-task learning. By using multiple beamformers to extract the signals from different DOAs, the sound field is more diversely described, and specialised representations of target source and noises can be obtained. With labelled training data, the steering vector is estimated based on the cross-power spectra (CPS) and the signal presence probability (SPP), which eliminates the need of knowing the array geometry. We design two networks for sound event localization (SED) and sound source localization (SSL), and use a multi-task learning scheme for SED, in which the SSL-related task act as a regularization. We conduct the experiments using the database of DCASE2019 SELD task, and the results show that the proposed method can achieve the state-of-art performance.


**The JD AI Speaker Verification System for the FFSVC 2020 Challenge**

Ying Tong(JD AI Research), Wei Xue(JD AI Research), Shanluo Huang(JD AI Research), Lu Fan(JD AI Research), Chao Zhang(JD AI Research), Guohong Ding(JD AI Research) and Xiaodong He(JD AI Research)

Abstract: This paper presents the development of our systems for the Interspeech 2020 Far-Field Speaker Verification Challenge (FFSVC). Our focus is the task 2 of the challenge, which is to perform far-field text-independent speaker verification using a single microphone array. The FFSVC training set provided by the challenge is augmented by pre-processing the far-field data with both beamforming, voice channel switching, and a combination of weighted prediction error (WPE) and beamforming. Two open-access corpora, CHData in Mandarin and VoxCeleb2 in English, are augmented using multiple methods and mixed with the augmented FFSVC data to form the final training data. Four different model structures are used to model speaker characteristics: ResNet, extended time-delay neural network (ETDNN), Transformer, and factorized TDNN (FTDNN), whose output values are pooled across time using the self-attentive structure, the statistic pooling structure, and the GVLAD structure. The final results are derived by fusing the adaptively normalized scores of the four systems with a two-stage fusion method, which achieves a minimum of the detection cost function (minDCF) of 0.3407 and an equal error rate (EER) of 2.67% on the development set of the challenge.


**SkipConvNet: Skip Convolutional Neural Network for Speech Dereverberation using Optimally Smoothed Spectral Mapping**

Vinay Kothapally(The University of Texas at Dallas - Center for Robust Speech Systems (CRSS)), Wei Xia(University of Texas at Dallas), Shahram Ghorbani(Center for Robust Speech Systems (CRSS), University of Texas at Dallas, Richardson, TX 75080), John H.L. Hansen(Univ. of Texas at Dallas; CRSS - Center for Robust Speech Systems), Wei Xue(JD AI Research) and Jing Huang(JD AI Research)

Abstract: The reliability of using fully convolutional networks (FCNs) has been successfully demonstrated by recent studies in many speech applications. One of the most popular variants of these FCNs is the 'U-Net', which is an encoder-decoder network with skip connections. In this study, we propose 'SkipConvNet' where we replace each skip connection with multiple convolutional modules to provide decoder with intuitive feature maps rather than encoder's output to improve the learning capacity of the network. We also propose the use of optimal smoothing of power spectral density (PSD) as a pre-processing step, which helps to further enhance the efficiency of the network. To evaluate our proposed system, we use the REVERB challenge corpus to assess the performance of various enhancement approaches under the same conditions. We focus solely on monitoring improvements in speech quality and their contribution to improving the efficiency of back-end speech systems, such as speech recognition and speaker verification, trained on only clean speech. Experimental findings show that the proposed system consistently outperforms other approaches.


**Efficient WaveGlow: An Improved WaveGlow Vocoder with Enhanced Speed**

Wei Song(JD AI Research), Guanghui Xu(JD AI Research), Zhengchen Zhang(JD.com), Chao Zhang(University of Cambridge), Xiaodong He(JD AI Research) and Bowen Zhou(JD AI Research)

Abstract: Neural vocoder, such as WaveGlow, has become an important component in recent high-quality text-to-speech (TTS) systems. In this paper, we propose Efficient WaveGlow (EWG), a flow-based generative model serving as an efficient neural vocoder. Similar to WaveGlow, EWG has a normalizing flow backbone where each flow step consists of an affine coupling layer and an invertible 1x1 convolution. To reduce the number of model parameters and enhance the speed without sacrificing the quality of the synthesized speech, EWG improves WaveGlow in three aspects. First, the WaveNet-style transform network in WaveGlow is replaced with an FFTNet-style dilated convolution network. Next, to reduce the computation cost, group convolution is applied to both audio and local condition features. At last, the local condition is shared among the transform network layers in each coupling layer. As a result, EWG can reduce the number of floating-point operations (FLOPs) required to generate one-second audio and the number of model parameters both by more than 12 times. Experimental results show that EWG can reduce real-world inference time cost by more than twice, without any obvious reduction in the speech quality.

Audio samples of this paper can be found at [Efficient WaveGlow Audio Samples](http://weixsong.github.io/demos/EfficientWaveGlow/index.html).


