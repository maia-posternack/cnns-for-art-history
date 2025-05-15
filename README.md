Python code for my HIST 2029 Final Paper exploring how Convolutional Neural Networks make classification decisions for different artistic genres

1. Data comes from https://huggingface.co/datasets/huggan/wikiart a pre-labeled dataset of 80k+ artworks
2. I preprocess that data and narrow down to to *impressionist* and *cubist* artworks.
3. I run a CNN on these artworks to classify them into the two categories
4. I create grad-CAM visualizations, depicting what the CNN found important in the classification process

400 of the Grad-CAM images are included in this repository due to storage constraints. The code attached would allow you to produce 4000

To run: 

Simply downloading this repository will allow you to view a pre-run jupyter notebook that includes all relevent outputs
To run the notebook yourself you will need to 
1. `python3 -m venv venv`
2. `source venv/bin/activate`
3. `pip install datasets torchvision matplotlib torch`
4. Choose this venv to be your kernel and run!
