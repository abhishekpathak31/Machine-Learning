# Machine-Learning
Animals Recognition


Concepts used :- CNN
DATASET :- (http://www.superdatascience.com/wp-content/uploads/2017/04/Convolutional_Neural_Networks.zip)
Note:- The above mentioned dataset is only for two animals cats and DOG ,but the algorithm designed is for three animals.


if you want to add more, 
**change output_dim = *desired number of animals/humans* in the defined output layer**

Program run on:
- Spyder
- Python 3.5

Libraries used: 
- Keras 
- scikit-learn 
- Tensorflow


Steps Applied : 
1. Convolution 
2. Pooling 
3. First Two Steps repeated to increase accuracy 
4. Flattening 
5. Full Connection Establishment 
6. Fitting Image to CNN


NOTE: *The program was run on windows 10, 64 bit. The epoch rate was pretty slow, to fix the issue, in fit_generator, 'steps_per_epoch' and 'validation_steps' were divied by its batch_size. It decreased the overall execution time.*

