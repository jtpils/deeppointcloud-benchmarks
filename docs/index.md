![Screenshot](logo.png)


This is a framework for running common deep learning models for point cloud analysis tasks against classic benchmark. It heavily relies on [```Pytorch Geometric```](https://github.com/rusty1s/pytorch_geometric) and [```Facebook Hydra library```](https://hydra.cc/docs/intro).

Here is the link toward the [```Github```](https://github.com/nicolas-chaulet/deeppointcloud-benchmarks/tree/doc) project.

We aim at building a tool for both benchmarking SOTA models and to efficiently pursue research for point cloud analysis with hope to bring them into real-life applications.


<h2>Core features</h2>

* ```Task driven``` implementation with dynamic model and dataset resolution from arguments
* ```Unet base``` implementation for simplying new model creation [more unet base are coming]
* ```Base Convolution``` to simplify new convolution implementation
* ```Base sampler / neigbours finder``` collections
* ```2 API``` to write models ```(compact / sequential)``` to ease reproducibility
* Several visualiation tool ```(tensorboard, wandb)``` and ```dynamic metric-based model checkpointing``` for one to customize
* ```Dynamic customized placeholder resolution``` for smart model definition

<h2>Current supported models</h2>

* [```RandLA-Net```: Efficient Semantic Segmentation of Large-Scale Point Clouds ](https://arxiv.org/pdf/1911.11236.pdf)
* [```Relation-Shape Convolutional (RSConv)``` Neural Network for Point Cloud Analysis](https://arxiv.org/abs/1904.07601)
* [```KPConv```: Flexible and Deformable Convolution for Point Clouds](https://arxiv.org/abs/1904.08889)
* [```PointCNN```: Convolution On X-Transformed Points](https://arxiv.org/abs/1801.07791)
* [```PointNet++```: Deep Hierarchical Feature Learning on Point Sets in a Metric Space](https://arxiv.org/abs/1706.02413)

and much more to come ...


<h2>Current supported tasks</h2>

* Segmentation
* Classification


![Screenshot](https://uploads-ssl.webflow.com/5a9058c8f7462d00014ad4ff/5a988ceadc6c9b0001cb2511_point%20cloud.JPG)


