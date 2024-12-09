## Dataset
The project utilizes the **Flickr8k dataset**, consisting of over 8,000 images paired with five descriptive captions each. This dataset is ideal for generating textual descriptions for images. All dataset files are organized in the `input` directory for seamless access.

## Training
Captions are tokenized and padded to a maximum length of 35 words for uniformity. A custom data generator is employed to load and process the data in batches during training, optimizing memory usage. The dataset is split into training (90%) and validation (10%) sets to evaluate the model's performance effectively.

## Results
The trained model generates captions that closely describe the content of the images. For example, for an image of a dog playing with a frisbee, the model might produce:  
*"A dog playing with a frisbee in a park."*  
These results highlight the model's ability to align image features with natural language.

## Acknowledgements
This project benefited greatly from online tutorials and research papers on image captioning. Gratitude is extended to the creators of the **Flickr8k dataset** and the **TensorFlow/Keras community** for providing tools and pre-trained models that supported the development process.
