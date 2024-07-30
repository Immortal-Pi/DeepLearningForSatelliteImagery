
# Satellite Imagery

Building a Deep Learning model using U-Net architecture for satellite images.


## Demo

Satellite Segmentaion Prediction - a Hugging Face Space by immortalPi
https://huggingface.co/spaces/immortalPi/Satellite-Segmentaion-Prediction


## Documentation

	• satellite dataset - dubai
	• Convert the image sizes 
	• masked segmentation images
	• data preparation for deep learning
		○ Patchify 
	• U-net model
		○ Encoding and decoder 
	• Custom Loss function and metrics 
	• Segmentation model
	• Training deep learning model
	• Model history and prediction
	• Activation outputs and gradients for each tensorflow layer 
	• Netron - visualize the model
	• ML training diagnostics (Local) - https://wandb.ai/site
		○ https://wandb.ai/26-amruth-immortalpi/satellite-segmentation-dubai-images 
	• Apply remote debugging with weights and biases 
	• Activation output for each layer 
		○ Keras activation + gradients  Keract
		○ Layer wise visualization 
	• Model deployment at hugging face



## API Reference

#### Weights and biases 

```https
  https://wandb.ai/26-amruth-immortalpi/satellite-segmentation-dubai-images
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | f6696212866a9b097f6468d5cae2901364cf7713 |

#### hugging Face

```https
  https://huggingface.co/spaces/immortalPi/Satellite-Segmentaion-Prediction
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `upload images`      | `image` | upload custom images to check |




# Screenshots

## objective
![objective1](https://github.com/amruthpai123/DeepLearningForSatelliteImagery/blob/main/screenshots/objective1.JPG)

![objective2](https://github.com/amruthpai123/DeepLearningForSatelliteImagery/blob/main/screenshots/objective2.JPG)

## model
https://netron.app/ (load the model for viz)

![model](https://github.com/amruthpai123/DeepLearningForSatelliteImagery/blob/main/screenshots/satellite_segmentation_full.h5.png)
## weights and biases
![wanb](https://github.com/amruthpai123/DeepLearningForSatelliteImagery/blob/main/screenshots/wandb.jpg)
## hugging face
![huggingface](https://github.com/amruthpai123/DeepLearningForSatelliteImagery/blob/main/screenshots/huggingFace.JPG)


## Optimizations

needs Optimizations

## custom loss function 

cross entropy loss extension

![loss](https://github.com/amruthpai123/DeepLearningForSatelliteImagery/blob/main/screenshots/lossFunction.JPG)

