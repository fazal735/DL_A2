# DL_A2

model architecture
number of layers=5
activations: ReLU,GeLU,SiLU
max pooling and drop out applied at each layer
test model without a dropout in 1st layer but no significant difference 
1 dense layer
output layerof 10 classes



**hyper parameters**


Kernel Size (Size of Filters): [[3,3,3,3,3], [3,5,5,7,7], [7,7,5,5,3]]


Dropout: [0.2, 0.3]


Activation Function: ['ReLU', 'GELU', 'SiLU', 'Mish']


Batch Normalization: [Yes, No]


Filter Organization: [[32,32,32,32,32], [128, 128, 64, 64,32], [32, 64,128,256,512]]


Data Augmentation:[Yes, No]


Number of nodes in dense layer : [128, 256]





best hyperparameter

ks[3, 5, 5, 7, 7]


ac-silu_drop-0.3_


fs-[32, 32, 32, 32, 32]_


bn-Yes_dence-128 ks[3, 5, 5, 7, 7]


ac-silu_drop-0.3_


fs-[32, 32, 32, 32, 32]_


bn-Yes_


dence-128





links:


https://wandb.ai/mfazal735-iit-madras-foundation/DL%20A2/reports/DL_A2-mm24d952--VmlldzoxMjM1ODc3OA


https://wandb.ai/mfazal735-iit-madras-foundation/DL_A2(partB)/reports/part2--VmlldzoxMjM1ODc5Nw
