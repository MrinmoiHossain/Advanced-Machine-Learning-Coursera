#### 1. Choose correct statements about convolutional layer:
##### Ans: 
- Convolutional layer is a special case of a fully-connected layer
- Convolutional layer works the same way for every input patch
#### 2. Choose correct statements about pooling layer:
##### Ans: 
- Pooling layer provides translation invariance
- Pooling layer can reduce spatial dimensions (width and height of the input volume)
#### 3. Back-propagation for convolutional layer first calculates the gradients as if the kernel parameters were not shared and then...
##### Ans: Takes a sum of gradients for each shared parameter
#### 4. Suppose you have a 10x10x3 colour image input and you want to stack two convolutional layers with kernel size 3x3 with 10 and 20 filters respectively. How many parameters do you have to train for these two layers? Don't forget bias terms!
##### Ans: (3*3*3+1)*10+(3*3*10+1)*20 = 2100
#### 5. What receptive field do we have after stacking nnn convolutional layers with kernel size k×k×k and stride 1? Layers numeration starts with 1. The resulting receptive field will be a square, input its side as an answer.
##### Ans: k*n-n+1