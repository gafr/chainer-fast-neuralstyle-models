# chainer-fast-neuralstyle-models

Some models trained by different people using the [chainer fast neuralstyle app](https://github.com/yusuketomoto/chainer-fast-neuralstyle) by yusuketomoto.
Please note, there has been a change on how the models are trained which makes them not suitable for the most recent version relased. Will update here soon.

The animated gifs have been created with a simple "real-time" video capture wrapper written in python. The code is available at https://github.com/gafr/chainer-fast-neuralstyle-video

## Compatible with old code ([0d96350](https://github.com/yusuketomoto/chainer-fast-neuralstyle/tree/0d96350))

ModelName | Reference | Parameters | Style | Samples
--- | --- | --- | --- | ---
starrynight | [chainer-fast-neuralstyle](https://github.com/yusuketomoto/chainer-fast-neuralstyle) | unknown |![starrynight](images/starrynight-style.jpg) | ![starrynight](images/starrynight.jpg) ![starry](images/starrynight.gif?raw=true)
cubist | [cubistMirror](https://github.com/genekogan/CubistMirror/) | unknown |![cubist](images/cubist-style.jpg?raw=true) |<img src="images/cubist.jpg?raw=true" alt="alt text" width="1500"> ![cubist](images/cubist.gif?raw=true)
hokusai | [cubistMirror](https://github.com/genekogan/CubistMirror/) | unknown | ![hokusai](images/hokusai-style.jpg?raw=true)| ![hokusai](images/hokusai.jpg?raw=true)
hundertwasser | - | 1000 training images, 2 epoches, training: size 512 (full) | ![hundertwasser](images/hundertwasser-style.jpg?raw=true)| ![](images/hundertwasser.jpg?raw=true)
kandinsky | uploaded by [6o6o](https://github.com/6o6o) | full coco training set, 2 epoches, training size 512 (cropped) | ![kandinsky](images/kandinsky.jpg?raw=true)| ![kandinski](images/kandinsky_e2_crop512.jpg?raw=true) ![kandinskigif](images/kandinsky_crop.gif?raw=true)
kandinsky | uploaded by [6o6o](https://github.com/6o6o) | full coco training set, 2 epoches, training size 512 (full) | ![kandinsky](images/kandinsky.jpg?raw=true)| ![kandinski](images/kandinsky_e2_full512.jpg?raw=true)
edtaonisl | uploaded by [6o6o](https://github.com/6o6o) | full coco training set, 2 epoches, training size 512 (cropped) | ![edtaonisl](images/edtaonisl.jpg)| ![edtaonisl](images/edtaonisl_e2_crop512.jpg) ![edtaonisl](images/edtaonisl.gif?raw=true)

## Compatible with new code

Model Name | Reference | Parameters | Style | Samples
--- | --- | --- | --- | ---
Kanagawa | [6o6o](https://github.com/6o6o) | full coco, 2 epochs, image_size 512 (crop) | ![kanagawa](images/kanagawa-style.jpg)| ![kanagawa](images/kanagawa.jpg)
Candy | [Heartsie](https://github.com/Heartsie) | full coco, 2.6 epochs, image_size 512 (crop) | ![candy](images/candy-style.jpg)| ![candy](images/candy.jpg)
Fur | [6o6o](https://github.com/6o6o) | full coco, 1 epoch, image_size 512 (crop) | ![fur](images/fur-style.jpg)| ![fur](images/fur.jpg)
Starry Night | [DylanAlloy](https://github.com/DylanAlloy) | full coco, 2 epochs, image_size 512 (crop) | ![starry](images/starry-style.jpg)| ![starry](images/starry.jpg)
