<pre>
Model: "Cifar10"
_________________________________________________________________
Layer (type)                 Output Shape              Param #   
=================================================================
input_13 (InputLayer)        [(None, 32, 32, 3)]       0         
_________________________________________________________________
conv2d_25 (Conv2D)           (None, 16, 16, 24)        312       
_________________________________________________________________
max_pooling2d_11 (MaxPooling (None, 8, 8, 24)          0         
_________________________________________________________________
conv2d_26 (Conv2D)           (None, 4, 4, 64)          6208      
_________________________________________________________________
conv2d_27 (Conv2D)           (None, 2, 2, 80)          20560     
_________________________________________________________________
flatten_9 (Flatten)          (None, 320)               0         
_________________________________________________________________
dense_40 (Dense)             (None, 1046)              335766    
_________________________________________________________________
dense_41 (Dense)             (None, 250)               261750    
_________________________________________________________________
dense_42 (Dense)             (None, 94)                23594     
_________________________________________________________________
dense_43 (Dense)             (None, 26)                2470      
_________________________________________________________________
dense_44 (Dense)             (None, 10)                270       
=================================================================
Total params: 650,930
Trainable params: 650,930
Non-trainable params: 0
_________________________________________________________________
</pre>
