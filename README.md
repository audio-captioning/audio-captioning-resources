# Resources for automated audio captioning

Welcome to the repository about automated audio captioning resources.
This repository aims at having an up-to-date list of resources for
automated audio captioning (AAC), ranging from AAC datasets to natural
language processing (NLP) related and audio processing tools and models. 

The repository is organized in three sectionsm, with a fourth one coming
later on. The first section is about AAC datasets. The second is about NLP
tools and models, and the third is about audio processing models and
tools. 

## Table of contents

1. [Automated audio captioning datasets](#automated-audio-captioning-datasets) 

   1.[Audio caption dataset](#audio-caption-dataset) 
   2.[AudioCaps dataset](#audioCaps-dataset) 
   3.[Clotho dataset](#clotho-dataset) 
  
2. [Natural language processing tools and models](#natural-language-processing-tools-and-models) 
3. [Audio processing tools and models](#audio-processing-tools-and-models) 

## Automated audio captioning datasets

At the moment, there are three AAC datasets. Here will be listed all three of them, in chronological order. 

### Audio caption dataset

Audio Caption dataset can be [found online](https://www.github.com/richermans/AudioCaption)
and consists of audio clips from two specific scenes, "Hospital" and "Car".
Audio Caption contains around 3700 audio clips from "Hospital" scene and
around 3600 audio clips from the "Car" scene. Every audio clip is
10 seconds long and is annotated with five captions. Audio Caption
offers two splits for each scene, a development and a evaluation one.
Additional information can be found at the corresponding
[GitHub repository of Audio Caption](www.github.com/richermans/AudioCaption)
and at the corresponding papers of Audio Caption.

References: 

1. M. Wu, H. Dinkel, and K. Yu, "Audio caption: Listen and tell," in 2019 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), May 2019, pp. 830–834
2. X. Xu, H. Dinkel, M. Wu, and K. Yu, "Audio Caption in a Car Setting with a Sentence-Level Loss," in arXiv:1905.13448 [cs.SD], 2019

### AudioCaps dataset

AudioCaps can also be [found online](https://audiocaps.github.io) and
consists of annotations of clips from the AudioSet dataset. AudioCaps
has around 40 000 audio clips of 10 seconds, organized in three splits;
a training slipt, a validation slipt, and a testing slipt. Training
split has around 38 000 audio clips, with one caption each. Validation
and testing splits have around 500 and 900 clips, respectively, each
clips annotated with five captions. Further information can be found
at the [web page of AudioCaps](https://audiocaps.github.io) and at
the corresponding paper.

References:

1. C. D. Kim, B. Kim, H. Lee, and G. Kim, "AudioCaps: Generating captions for audios in the wild,” in Proceedings of the 2019 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies, Volume 1 (Long and Short Papers), Minneapolis, Minnesota, Jun. 2019, pp. 119–132, Association for Computational Linguistics

### Clotho dataset

Clotho dataset can be [found online]() and consists of audio samples of
15 to 30 seconds duration, each audio sample having five captions of eight
to 20 words length. There is a total of 4981 audio samples in Clotho, with
24 905 captions (i.e. 4981 audio samples * 5 captions per each sample).
Clotho is built with focus on audio content and caption diversity, and the
splits of the data are not hampering the training or evaluation of methods.
All audio samples are from the Freesound platform, and captions are
crowdsourced using Amazon Mechanical Turk and annotators from English speaking
countries. Unique words, named entities, and speech transcription are
removed with post-processing. Further information can be found at the
corresponding paper. 

References: 

1. K. Drossos, S. Lipping, and T. Virtanen, "Clotho: An audio captioning dataset," in ICASSP 2020-2020 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP). IEEE, 2020, pp. 736–740