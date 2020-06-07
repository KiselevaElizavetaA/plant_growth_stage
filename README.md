# Deep Learning techniques for plant growth classification

Image-based phenotyping technologies have been rapidly developed in plant science recently, they provide a great potential for agriculture.

The goal of the study is to develop models for effective prediction of plant biomass, and classification of plant growth stages, based on labeled visual data. For that we are planning to use different promising Deep Learning techniques, such as CNN and LSTM.

![https://www.lightrail3.com/light-movers-equal-faster-plant-growth/](https://sun9-39.userapi.com/e7otZk5LvI-f3u0Vc04JBGbidvBG7kodBBxCtg/51Abg4YrZzU.jpg)

## Data

* [Tomatoes](https://github.com/DmitriiShadrin/TGD-Tomato-Growth-Dynamics)
* [Weeds](https://vision.eng.au.dk/leaf-counting-dataset/)

![Example](/images/fig2.png)

The problem is data is very unbalanced.
![Class unbalanced](/images/fig1.png)

## Methods
### Data augmentation
* Resize (128, 128);
* Random Affine transformation (20);
* Random Horizontal Flip;
* Random Vertical Flip;
* Random Rotation (180);
* ColorJitter (brightness=0.3, contrast=0.4).

### Optimization Algorithm
Adam (lr=0.007)

### DenseNet architecture
Best results were achived by DensNet169 architecture.
![DensNet169 architecture](/images/table.png)

## Results
![Confusion matrix](/images/fig8.png)
