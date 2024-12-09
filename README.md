# CNN-and-LSTM

Project Completion Report
Analysing dataset by implementing and training two models: a CNN and an LSTM.

1. Data Processing
The image processing function for the film posters has been successfully implemented. The TensorFlow tf.data API was utilized to construct an efficient and optimized data processing pipeline. This pipeline ensures the smooth ingestion, augmentation, and batching of poster images for training. Additionally, the model's vocabulary was built using the encoder.adapt() method, facilitating better handling of text data. The entire data processing pipeline is now fully operational and optimized for performance.

2. Definition of the Models
The convolutional neural network (CNN) for film posters has been constructed and compiled according to the predefined model summary. All layer configurations, output shapes, and parameter counts were correctly implemented to align with the provided model architecture. For the film overviews, an embedding layer was successfully set up, and a Keras Sequential model was built using the layer specifications from the notebook. Both models are now ready for training and capable of processing their respective input types.

3. Training of the Models
The training process for both models was completed successfully. A set of callbacks was defined to log the models' progress, allowing for effective tracking and monitoring during training. Each model was trained for the specified number of epochs, achieving convergence and consistent improvements in accuracy and loss metrics over time.

4. Evaluation of the Models
The models have been thoroughly evaluated for performance. Using selected example films, the system displayed their posters, printed their overviews, and predicted their genres with high accuracy. The evaluation demonstrated that both the CNN for posters and the embedding-based text model for overviews are performing as expected, providing reliable and meaningful genre predictions. Visual and textual results were cross-checked to validate the accuracy of predictions.
