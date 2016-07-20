# chainer-fast-neuralstyle-models

Some models trained by different people using the [chainer fast neuralstyle app](https://github.com/yusuketomoto/chainer-fast-neuralstyle) by yusuketomoto.
Please note, there has been a change on how the models are trained which makes them not suitable for the most recent version relased. Will update here soon.

The animated gifs have been created with a simple "real-time" video capture wrapper written in python, will release the code shortly.

ModelName | Reference | Parameters | Style | Samples
--- | --- | --- | --- | ---
starrynight | [chainer-fast-neuralstyle](https://github.com/yusuketomoto/chainer-fast-neuralstyle) | unknown |![starrynight](images/starrynight-style.jpg) | ![starrynight](images/starrynight.jpg) ![starry](images/starrynight.gif?raw=true)
cubist | [cubistMirror](https://github.com/genekogan/CubistMirror/) | unknown |![cubist](images/cubist-style.jpg?raw=true) |<img src="images/cubist.jpg?raw=true" alt="alt text" width="1500"> ![cubist](images/cubist.gif?raw=true)
hokusai | [cubistMirror](https://github.com/genekogan/CubistMirror/) | unknown | ![hokusai](images/hokusai-style.jpg?raw=true)| ![](images/hokusai.jpg?raw=true)
hundertwasser | - | 1000 training images, 2 epoches, training: size 512 (full) | ![hokusai](images/hundertwasser-style.jpg?raw=true)| ![](images/hundertwasser.jpg?raw=true)
kandinsky | uploaded by [6o6o](https://github.com/6o6o) | full coco training set, 2 epoches, training size 512 (cropped) | ![hokusai](images/kandinsky.jpg?raw=true)| ![kandinski](images/kandinsky_e2_crop512.jpg?raw=true) ![kandinskigif](images/kandinsky_crop.gif?raw=true)
kandinsky | uploaded by [6o6o](https://github.com/6o6o) | full coco training set, 2 epoches, training size 512 (full) | ![hokusai](images/kandinsky.jpg?raw=true)| ![kandinski](images/kandinsky_e2_full512.jpg?raw=true)
edtaonisl | uploaded by [6o6o](https://github.com/6o6o) | full coco training set, 2 epoches, training size 512 (cropped) | ![edtaonisl](images/edtaonisl.jpg)| ![edtaonisl](images/edtaonisl_e2_crop512.jpg) ![edtaonisl](images/edtaonisl.gif?raw=true)
