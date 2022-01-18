# CNN_Notes

| Header | Link |
| :---: | :---: |
| Components | <a href = "https://jovian.ai/paulbindass/convolutional-neural-network-world"> CNN BASIC COMPONENTS</a> |
| Visual Representation | <a href = "https://poloclub.github.io/cnn-explainer/"> CNN EXPLAINER</a> |


# CNN NETWORKS

| NETWORK | YEAR | ARCHITECTURE | Whats NEW |
| :---: | :---: | :---: | :---: |
|LENET|1998|32X32 --> 5X5[Kernel] --> 28X28 --> AP --> 14X14 --> 5X5[Kernel] --> 10X10 --> AP --> 5X5 --> FC[tanh] --> FC[tanh] --> SOFTMAX|
|ALEXNET|2012|227X227 --> 55X55 --> 27X27 --> 13X13 --> 6X6 --> FC --> FC|1.LRN<BR>2.RELU<br>3.11X11 & 5X5 Filter<br>4.Dropout<br>|
|VGG|2014|224X224 --> 112X112 --> 56X56 --> 28X28 --> 14X14 --> 7X7 --> FC --> FC --> FC|1.3X3 filter<BR>2.weight decay<br>3.L2 Reguralisation<br>4.Dropout<br>|
  
  
# IMAGENET Competition
  
| YEAR | WINNER |
| :---: | :---: |
| 2012 |	ALEXNET	15.3 |
| 2013 |	ZFNET	11.2 |
| 2014 | 	INCEPTION V1 (GoogLeNet)<BR>VGG NET (Runner up) |
| 2015 | 	ResNet	3.57 |
| 2016 | 	ResNeXt	4.1 |
| 2017 | 	SENet	2.251 |
| 2018 | 	PNASNet-5	3.8 |
