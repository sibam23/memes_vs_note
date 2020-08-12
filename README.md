# memes_vs_note

### ConvNet Architecture
Conv Layer - F(5x5)S(1x1)C(3,32)  
Conv Layer - F(5x5)S(1x1)C(32,48)  
Max Pool - F(2x2)S(2x2)  
Conv Layer - F(5x5)S(1x1)C(48,64)    
Conv Layer - F(5x5)S(1x1)C(64,96)   
Max Pool - F(2x2)S(2x2)  
Conv Layer - F(5x5)S(4x4)C(96,120)  
Dense - C(1080,250)  
Dense - C(250,2)  

#### Accuracy
Train set - 96.8  
Test set - 98  

### Numpy Architecture
Dense layer - C(12288,2500)  
Dense layer - C(2500,1)  

#### Accuracy 
Train set - 62  
Test set - 74  


