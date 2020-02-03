# The Fastai Extensions Repository

A centralized repository for non-official [fastai](https://docs.fast.ai/) extensions.
All extensions are designed for fastai V1 unless told otherwise.

*Do not hesitate to send a PR of start an issue to add elements to this list.*

## Domain specific
- [timeseriesAI](https://github.com/timeseriesAI/timeseriesAI) a library to help you apply Deep Learning to your time series/ sequential datasets, in particular Time Series Classification (TSC) and Time Series Regression (TSR) problems ([discussion](https://forums.fast.ai/t/time-series-sequential-data-study-group/))
- [Fast AI Audio](https://github.com/mogwai/fastai_audio) allow you to quickly and easily build machine learning models for a wide variety of audio applications ([discussion](https://forums.fast.ai/t/deep-learning-with-audio-thread/))
- [Fast AI Audio V2](https://github.com/rbracco/fastai2_audio) (**V2**) an audio module for fastai V2, currently under development ([discussion](https://forums.fast.ai/t/fastai-v2-audio/))

## Callbacks
- [BatchLossFilter](https://github.com/oguiza/fastai_extensions/blob/master/03_BatchLossFilter.ipynb) speed-up learning by focussing on the harder samples ([discussion](https://forums.fast.ai/t/meet-batchlossfilter-a-new-technique-to-speed-up-training/56621))
- [Manifold mixup](https://github.com/nestordemeure/ManifoldMixup) applies mixup on inner layers for improved benefits and aplicability to arbitrary input types ([discussion](https://forums.fast.ai/t/mixup-data-augmentation/22764/53?u=nestordemeure))
- [Cutout, Ricap and Cutmix](https://github.com/oguiza/fastai_extensions/blob/master/01_data_augmentation_notebook.ipynb) image data augmentation techniques ([discussion](https://forums.fast.ai/t/cutmix-mixup/))
- [Blend](https://github.com/oguiza/fastai_extensions/blob/master/02_data_augmentation_blend.ipynb) image data augmentation that generalizes MixUp, Cutout, CutMix, RICAP and allows for data augmentation rate scheduling ([discussion](https://forums.fast.ai/t/data-augmentation-dynamic-blend/))
- [MixMatch](https://github.com/oguiza/fastai_extensions/blob/master/04a_MixMatch_extended.ipynb) state-of-the-art semi-supervised learning ([blogpost](https://github.com/noachr/MixMatch-fastai/blob/master/MixMatch%20Blog.ipynb), [discussion](https://forums.fast.ai/t/semi-supervised-learning-ssl-uda-mixmatch-s4l/))
- [Curriculum Learning Dropout](https://github.com/lessw2020/Curriculum-Learning-Dropout) dropout scheduler ([discussion](https://forums.fast.ai/t/improved-loss-with-curriculum-learning-paper-and-video/47337))

## Optimizers
- [Ranger](https://github.com/lessw2020/Ranger-Deep-Learning-Optimizer) a synergistic optimizer combining RAdam (Rectified Adam) and LookAhead ([discussion](https://forums.fast.ai/t/meet-ranger-radam-lookahead-optimizer))

## Models
- [TabNet](https://github.com/mgrankin/fast_tabnet) (**V2**) attention-based network for tabular data ([discussion](https://forums.fast.ai/t/tabnet-with-fastai-v2/))
- [MXResNet](https://github.com/lessw2020/mish/blob/master/mxresnet.py) FastAI's XResnet modified to use Mish activation function 
- [res2net plus](https://github.com/lessw2020/res2net-plus) Res2Net architecture with improved stem and Mish activation function ([discussion](https://forums.fast.ai/t/res2net-with-some-improvements-and-implementation/))

## Activation functions
- [Mish](https://github.com/lessw2020/mish) Mish Deep Learning Activation Function ([discussion](https://forums.fast.ai/t/meet-mish-new-activation-function-possible-successor-to-relu/))
