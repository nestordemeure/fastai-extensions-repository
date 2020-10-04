# [The Fastai Extensions Repository](https://forums.fast.ai/t/unofficial-fastai-extensions-repository/)

A centralized repository to improve the discoverability of non-official [fastai](https://docs.fast.ai/) extensions.
All extensions are designed for fastai V2 unless told otherwise.

*Do not hesitate to send a PR of start an issue to add elements to this list.*

## Domain specific
- **TimeseriesAI** ([repo-tcapelle](https://github.com/tcapelle/timeseries_fastai) / [repo-oguiza](https://github.com/timeseriesAI/timeseriesAI) / [repo-fast-track](https://github.com/ai-fast-track/timeseries) / [discussion](https://forums.fast.ai/t/timeseries/55861)) a library to help you apply Deep Learning to your time series/ sequential datasets, in particular Time Series Classification (TSC) and Time Series Regression (TSR) problems
- **Fast AI Audio** ([repo](https://github.com/rbracco/fastai2_audio) / [discussion](https://forums.fast.ai/t/fastai-v2-audio/)) allow you to quickly and easily build machine learning models for a wide variety of audio applications
- **MetaAI** ([repo-V1](https://github.com/Atom-101/MetaAI) / [discussion](https://forums.fast.ai/t/an-extension-of-fastai-for-meta-learning-algorithms/)) meta-learning algorithms to train a model on a variety of learning tasks, such that it can solve new learning tasks using only a small number of training samples

## Models
- **TabNet** ([repo](https://github.com/mgrankin/fast_tabnet) / [discussion](https://forums.fast.ai/t/tabnet-with-fastai-v2/)) attention-based network for tabular data
- **FastHug** ([repo](https://github.com/morganmcg1/fasthugs) / [discussion](https://forums.fast.ai/t/fasthugs-fastai-v2-and-huggingface-transformers/)) use fastai-v2 with HuggingFace's pretrained transformers
- **Fastai2 Tabular Hybrid** ([repo](https://github.com/muellerzr/fastai2_tabular_hybrid) / [discussion](https://forums.fast.ai/t/fastai-v2-tabular/53530/213)) hybrid approaches to supporting more datatypes with fastai2 tabular
- **TabularGP** ([repo](https://github.com/nestordemeure/tabularGP) / [discussion](https://forums.fast.ai/t/tabulargp-gaussian-processes-with-fastai/)) gaussian process for tabular data
- **Fastseq** ([repo](https://github.com/takotab/fastseq) / [discussion](https://forums.fast.ai/t/time-series-sequential-data-study-group/29686/600)) implements the N-Beats time serie forecasting model
- **Mish** ([repo](https://github.com/digantamisra98/Mish) / [discussion](https://forums.fast.ai/t/meet-mish-new-activation-function-possible-successor-to-relu/)) Mish Deep Learning Activation Function

## Callbacks
- **Manifold mixup and Output mixup** ([repo](https://github.com/nestordemeure/ManifoldMixupV2) / [discussion](https://forums.fast.ai/t/mixup-data-augmentation/22764/53)) applies mixup on inner layers for improved benefits and aplicability to arbitrary input types
- **BatchLossFilter** ([repo-V1](https://github.com/oguiza/fastai_extensions/blob/master/03_BatchLossFilter.ipynb) / [discussion](https://forums.fast.ai/t/meet-batchlossfilter-a-new-technique-to-speed-up-training/56621)) speed-up learning by focussing on the harder samples
- **Cutout, Ricap and Cutmix** ([repo-V1](https://github.com/oguiza/fastai_extensions/blob/master/01_data_augmentation_notebook.ipynb) / [discussion](https://forums.fast.ai/t/cutmix-mixup/)) image data augmentation techniques
- **Blend** ([repo-V1](https://github.com/oguiza/fastai_extensions/blob/master/02_data_augmentation_blend.ipynb) / [discussion](https://forums.fast.ai/t/data-augmentation-dynamic-blend/)) image data augmentation that generalizes MixUp, Cutout, CutMix, RICAP and allows for data augmentation rate scheduling
- **MixMatch** ([repo-V1](https://github.com/oguiza/fastai_extensions/blob/master/04a_MixMatch_extended.ipynb) / [discussion](https://forums.fast.ai/t/semi-supervised-learning-ssl-uda-mixmatch-s4l/)) state-of-the-art semi-supervised learning

## Interpretation
- **FastShap** ([old fork](https://github.com/nestordemeure/fastshap) / [discussion](https://forums.fast.ai/t/feature-importance-in-deep-learning/42026/64)) using the SHAP interpretability library with fastai (now merged with [fastinference](https://github.com/muellerzr/fastinference))
- **The Colorful Dimension** ([repo-V1](https://github.com/artste/colorfuldim) / [discussion](https://forums.fast.ai/t/the-colorful-dimension/))  charts made by plotting the activations histogram epoch by epoch, coloring the pixel according to log of intensity
- **The Twin Peaks Chart** ([repo-V1](https://github.com/artste/colorfuldim) / [discussion](https://forums.fast.ai/t/the-twin-peaks-chart/)) a tool to evaluate the health of your classification model in real time
- **Tensorboard Callback** ([repo-V1](https://github.com/Pendar2/fastai-tensorboard-callback) / [discussion](https://forums.fast.ai/t/tensorboard-callback-for-fastai/)) logs model and training information to display them with tensorboard
- **FastAI-LIME** ([repo-V1](https://github.com/anurags25/FastAI-LIME)) interpreting fastai CNN models using LIME
- **Feature importance** ([repo-V1](https://github.com/nestordemeure/permutationImportance) / [discussion](https://forums.fast.ai/t/feature-importance-in-deep-learning/)) computing feature importance for tabular learners using the permutation method

## Hyperparameters
- **Batch size finder** ([repo](https://github.com/hal-314/fastai-batch-size-finder) / [discussion](https://forums.fast.ai/t/batch-size-finder-from-openai-implemented-using-fastai/57620)) batch size finder from OpenAI
- **wd finder** ([repo-V1](https://github.com/DrHB/fastai_wd)) an extension of the learning rate finder to find a proper weight decay by grid search
- **Curriculum Learning Dropout** ([repo-V1](https://github.com/lessw2020/Curriculum-Learning-Dropout) / [discussion](https://forums.fast.ai/t/improved-loss-with-curriculum-learning-paper-and-video/47337)) dropout scheduler

## Inference
- **Fastinference** ([repo](https://github.com/muellerzr/fastinference) / [discussion](https://forums.fast.ai/t/a-walk-with-fastai2-fastinference-mini-series/73277)) a collection of inference modules for fastai including inference speedup and interpretability
- **Fastinference-onnx** ([repo](https://github.com/muellerzr/fastinference_onnx)) an ONNX only version of fastai
- **fastinference-pytorch** ([repo](https://github.com/muellerzr/fastinference_pytorch)) a PyTorch-only version of fastai

## Optimizers
- **Ranger** ([repo](https://github.com/lessw2020/Ranger-Deep-Learning-Optimizer) / [discussion](https://forums.fast.ai/t/meet-ranger-radam-lookahead-optimizer)) a synergistic optimizer combining RAdam (Rectified Adam), LookAhead and Gradient Centralization

## Notebook
- **DDip** ([repo](https://github.com/philtrade/Ddip) / [discussion](https://forums.fast.ai/t/distributed-multi-gpu-training-with-fastai-in-jupyter-notebook/)) iPython extension to enable PyTorch's Distributed Data Parallel in fastai's notebooks 

## Deployment
- **Fastai serving** ([repo](https://github.com/developmentseed/fastai-serving) / [discussion](https://forums.fast.ai/t/fastai-serving/)) a Docker image for serving fastai models, mimicking the API of Tensorflow Serving
- **Fastai2 Starlette** ([repo](https://github.com/muellerzr/fastai2-Starlette)) a starting point to deploy models with Starlette
