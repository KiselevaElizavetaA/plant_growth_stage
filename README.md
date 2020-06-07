# Deep Learning techniques for plant growth classification

Image-based phenotyping technologies have been rapidly developed in plant science recently, they provide a great potential for agriculture.

* Weeds are nuisance on the farmland, as they compete for plant nutrient
* Farmers must  know the weeds’ conditions on the field  in order to spray optimally, and minimize herbicide usage on soil
* They must maintain weed control, by targeting specific weeds.

Effective estimation of weed growth stage for farmer to determine the best time for applying herbicide to specific weeds. i.e Optimal weed eradication.

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

![Confusion matrix](/images/output1.png)


### Transfer learning
We have high hopes for the transfer method, but unfortunately we have not yet been able to obtain impressive results using this method.

![Confusion matrix](/images/image_2020-06-07_21-10-11.png)

For more detales, please check DL_Final_Project.pdf
