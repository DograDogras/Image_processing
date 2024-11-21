Orinal Datasets can be found on:
httpsimages.cvsearch-labeled-image-dataset

I've removed a few pictures from the River dataset in the 
test section as they would not be useful for a binary classifier
for rivers and forests.

I've chosen rivers and forests for a classifier because in a lot of 
river pictures you can see forestry, so the model would have
to be trained to identify rivers despite having forests beside it.
Creating the additional possibility of inducing False Positives.