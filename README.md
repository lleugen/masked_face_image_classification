# masked_face_image_classification
using cnns to classify images of people who are wearing a mask or not

## Repository content
* Report on solution development
* L2 parameter value search notebook
* Image classification notebook

## Problem description:
### Input
* Images of people (groups or single, from close up or farther away)
* A json file with labels for training set images
* [link to dataset](https://drive.google.com/file/d/1u88rl7w7osUeSyQfUIisTA6_nbz1DNGP/view?usp=sharing)
### Output
3 classes:
* all people are wearing a mask
* some people are not wearing a mask
* nobody is wearing a mask

## Solution approach
We used transfer learning from the VGG16 model. We applied L2 regularizer and did combinatorial search for finding the optimal parameter value. We used callbacks for controlling the training process. The final result achieved an accuracy of 0.92 on the test dataset.

## Contributors
[Eugenio Ostrovan](https://github.com/lleugen) and [Dennis Motta](https://github.com/Desno365)

