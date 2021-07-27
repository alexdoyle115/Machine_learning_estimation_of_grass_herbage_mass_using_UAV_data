# Machine_learning_estimation_of_grass_herbage_mass_using_UAV_data

Grazed grass is the most cost efficient feed available in ruminant production systems but can be difficult to maximise utilisation due to seasonal growth rates and variation of biomass within fields. Regular estimation of herbage mass can be useful as a decision support tool to improve utilisation. The requirement of weekly estimation can be time consuming and established methods have been shown to be limited in terms of accuracy. Remote sensing is a non-destructive detection technology that has been used to survey crops at a field scale. Multi and hyperspectral sensor used in conjunction with development of a crop surface model have regularly been applied in agriculture. In this study the capability of deep learning models to estimate sward height from RGB images was evaluated. Deep learning is a modern technique from computer vision and data analysis. Two deep learning models were compared, the first a simple novel convolutional neural network and a model utilising transfer learning. The models took images labels with the sward height in millimetres and output the estimated sward height measurement. The results indicated that deep learning models were ineffective at predicting sward height based of aerial RGB images. Both models minimised error by estimating values close to the mean sward height. To examine if any relationship existed between sward height and the images, the visible normalised difference vegetation index transformation was used. It indicated that there was a significant relationship between the pixel values and the sward height, but it was also a poor estimator explaining 26% of the variance.  
