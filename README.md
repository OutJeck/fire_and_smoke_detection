# Fire and Smoke detection

In this work, we trained 2 models, one that involves fire, the other smoke.
Models are the same - you can see it in the code.
In addition, we used superpixel segmentation.


That is, they divided the images into superpixels, which we fed to the model and predicted to see if there was fire or smoke.


As for colors, ![#0000ff](https://via.placeholder.com/15/0000ff/000000?text=+) blue is smoke, ![#ff0000](https://via.placeholder.com/15/ff0000/000000?text=+) red is fire, and ![#00ff00](https://via.placeholder.com/15/00ff00/000000?text=+) green is smoke and fire at the same time.


Here you can see the results with segmentation:

![plot](./data/segmentation_results/photo0.jpg)
![plot](./data/segmentation_results/photo1.jpg)
![plot](./data/segmentation_results/photo2.jpg)
![plot](./data/segmentation_results/photo3.jpg)
![plot](./data/segmentation_results/photo4.jpg)
![plot](./data/segmentation_results/photo5.jpg)
![plot](./data/segmentation_results/photo6.jpg)


## Datasets used for classification

Fire model: [link 1](https://github.com/cair/Fire-Detection-Image-Dataset), [link 2](https://data.mendeley.com/datasets/gjmr63rz2r/1)

Smoke model: [link](http://smoke.ustc.edu.cn/datasets.htm)
