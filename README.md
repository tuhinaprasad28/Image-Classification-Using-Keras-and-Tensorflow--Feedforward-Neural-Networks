### Feedforward Neural Networks- Image Classification Using Keras and Tensorflow

Consider two models: 

(1.) A 2-layer feedforward neural network (i.e., 1 hidden layer with $f(x,W_1,b_1,W_2,b_2) = W_2\max(0,W_1x+b_1) + b_2$), and 

(2.) Same as before but with leaky ReLU ($f(x) = x$ if $x > 0$, else $ f(x) = 0.01*x$).

#### a.) Build the above classifiers using Keras and Tensorflow and solve the classification problem for MNIST/Fashion MNIST.
#### b.) Discuss how optimizer choice influences performance.
#### c.) What happens when the number of hidden units chosen is much smaller. Similarly, what happens when the number of hidden units chosen is much higher?
