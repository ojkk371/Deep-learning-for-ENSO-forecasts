# Deep learning for multi-year ENSO forecasts
**We will finish it in a week.**

##

## Architecture of the CNN model
```
3(Conv Layer) + 2(MP Layer)  
MP Layer : max-pooling Layer → Suppressing Model Overfitting  
```
![CNN](/Image/CNN_forecasts.PNG)

##

## Transfer learning
Transfer learning is the idea of overcoming the isolated learning paradigm and utilizing knowledge acquired for one task to solve related ones.  

Transfer learning has several benefits, but the main advantages are saving training time, better performance of neural networks (in most cases), and not needing a lot of data.  

##

## Approach to Transfer learning
```
1. Load in a pre-trained CNN model trained on a large dataset.  
2. Freeze parameters (weights) in model's lower convolutional layers.  
3. Add custom classifier with several layers of trainable parameters to model.  
4. Train classifier layers on training data available for task.  
```

##

## Extended Data Table
![table4](/Image/data_table_04.PNG)  
  
