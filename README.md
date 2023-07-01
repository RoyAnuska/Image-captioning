# Image-captioning
Image Captioning using Encoder-Decoder module in Pytorch

The process of creating a written description of an image is called image captioning. The captions are produced
using both computer vision and natural language processing. The dataset will be in the form [image → captions].
The dataset consists of input images and their corresponding output captions

Flicker-8k Dataset is being used in this project

Initially, a baseline architecture consisting of a CNN backbone as the encoder part and LSTM in the decoder part is used.
For the encoder, we experimented with the Inception V3 module and ResNET module and finally decided on the ResNET module as our encoder for the baseline architecture.

To have some improvement on the baseline architecture we introduced the attention mechanism and the performance was considerably improved. 

Please find more details on this project in the attachment. 
[Image Captioning Report.pdf](https://github.com/RoyAnuska/Image-captioning/files/11925995/Image.Captioning.Report.pdf)

Link to the Flicker-8k Dataset :- https://drive.google.com/drive/folders/1SfRf9D1YAda_Nh9hgNVFLxX5E06ZBqrv?usp=sharing


