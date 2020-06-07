# Deep Learning techniques for plant growth classification

Image-based phenotyping technologies have been rapidly developed in plant science recently, they provide a great potential for agriculture.

The goal of the study is to develop models for effective prediction of plant biomass, and classification of plant growth stages, based on labeled visual data. For that we are planning to use different promising Deep Learning techniques, such as CNN and LSTM.

![https://www.lightrail3.com/light-movers-equal-faster-plant-growth/](https://sun9-39.userapi.com/e7otZk5LvI-f3u0Vc04JBGbidvBG7kodBBxCtg/51Abg4YrZzU.jpg)

## Data

* [Tomatoes](https://github.com/DmitriiShadrin/TGD-Tomato-Growth-Dynamics)
* [Weed](https://vision.eng.au.dk/leaf-counting-dataset/)

## Methods
### Data augmentation
* Resize $(128, 128)$;
* Random Affine transformation (20);
* Random Horizontal Flip;
* Random Vertical Flip;
* Random Rotation (180);
* ColorJitter (brightness=0.3, contrast=0.4).


## Results
