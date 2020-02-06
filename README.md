# [The Fastai Extensions Repository](https://forums.fast.ai/t/unofficial-fastai-extensions-repository/)

A centralized repository to improve the discoverability of non-official [fastai](https://docs.fast.ai/) extensions.
All extensions are designed for fastai V1 unless told otherwise.

*Do not hesitate to send a PR of start an issue to add elements to this list.*

## Domain specific
- **TimeseriesAI** ([repo](https://github.com/timeseriesAI/timeseriesAI) / [discussion](https://forums.fast.ai/t/time-series-sequential-data-study-group/)) a library to help you apply Deep Learning to your time series/ sequential datasets, in particular Time Series Classification (TSC) and Time Series Regression (TSR) problems
- **Fast AI Audio** ([repo-V1](https://github.com/mogwai/fastai_audio) / [discussion-V1](https://forums.fast.ai/t/deep-learning-with-audio-thread/) / [repo-V2](https://github.com/rbracco/fastai2_audio) / [discussion-V2](https://forums.fast.ai/t/fastai-v2-audio/)) allow you to quickly and easily build machine learning models for a wide variety of audio applications

## Callbacks
- **BatchLossFilter** ([repo](https://github.com/oguiza/fastai_extensions/blob/master/03_BatchLossFilter.ipynb) / [discussion](https://forums.fast.ai/t/meet-batchlossfilter-a-new-technique-to-speed-up-training/56621)) speed-up learning by focussing on the harder samples
- **Manifold mixup and Output mixup** ([repo](https://github.com/nestordemeure/ManifoldMixup) / [discussion](https://forums.fast.ai/t/mixup-data-augmentation/22764/53)) applies mixup on inner layers for improved benefits and aplicability to arbitrary input types
- **Cutout, Ricap and Cutmix** ([repo](https://github.com/oguiza/fastai_extensions/blob/master/01_data_augmentation_notebook.ipynb) / [discussion](https://forums.fast.ai/t/cutmix-mixup/)) image data augmentation techniques
- **Blend** ([repo](https://github.com/oguiza/fastai_extensions/blob/master/02_data_augmentation_blend.ipynb) / [discussion](https://forums.fast.ai/t/data-augmentation-dynamic-blend/)) image data augmentation that generalizes MixUp, Cutout, CutMix, RICAP and allows for data augmentation rate scheduling
- **MixMatch** ([repo](https://github.com/oguiza/fastai_extensions/blob/master/04a_MixMatch_extended.ipynb) / [discussion](https://forums.fast.ai/t/semi-supervised-learning-ssl-uda-mixmatch-s4l/)) state-of-the-art semi-supervised learning

## Hyperparameters
- **wd finder** ([repo](https://github.com/DrHB/fastai_wd)) an extension of the learning rate finder to find a proper weight decay by grid search
- **Curriculum Learning Dropout** ([repo](https://github.com/lessw2020/Curriculum-Learning-Dropout) / [discussion](https://forums.fast.ai/t/improved-loss-with-curriculum-learning-paper-and-video/47337)) dropout scheduler

## Models
- **TabNet** ([repo-V2](https://github.com/mgrankin/fast_tabnet) / [discussion](https://forums.fast.ai/t/tabnet-with-fastai-v2/)) attention-based network for tabular data
- **Mish** ([repo](https://github.com/lessw2020/mish) / [discussion](https://forums.fast.ai/t/meet-mish-new-activation-function-possible-successor-to-relu/)) Mish Deep Learning Activation Function
- **MXResNet** ([repo](https://github.com/lessw2020/mish/blob/master/mxresnet.py)) FastAI's XResnet modified to use Mish activation function 
- **Res2net plus** ([repo](https://github.com/lessw2020/res2net-plus) / [discussion](https://forums.fast.ai/t/res2net-with-some-improvements-and-implementation/)) Res2Net architecture with improved stem and Mish activation function

## Optimizers
- **Ranger** ([repo](https://github.com/lessw2020/Ranger-Deep-Learning-Optimizer) / [discussion](https://forums.fast.ai/t/meet-ranger-radam-lookahead-optimizer)) a synergistic optimizer combining RAdam (Rectified Adam) and LookAhead

## Interpretation
- **The Colorful Dimension** ([repo](https://github.com/artste/colorfuldim) / [discussion](https://forums.fast.ai/t/the-colorful-dimension/))  charts made by plotting the activations histogram epoch by epoch, coloring the pixel according to log of intensity
- **The Twin Peaks Chart** ([repo](https://github.com/artste/colorfuldim) / [discussion](https://forums.fast.ai/t/the-twin-peaks-chart/)) a tool to evaluate the health of our model in real time
- **Feature importance** ([snippet](https://forums.fast.ai/t/feature-importance-in-deep-learning/42026/21) / [discussion](https://forums.fast.ai/t/feature-importance-in-deep-learning/)) computing feature importance for tabular learners

## Deployment
- **Fastai serving** ([repo](https://github.com/developmentseed/fastai-serving) / [discussion](https://forums.fast.ai/t/fastai-serving/)) a Docker image for serving fastai models, mimicking the API of Tensorflow Serving
