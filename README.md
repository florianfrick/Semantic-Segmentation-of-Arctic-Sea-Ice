# Semantic-Segmentation-of-Arctic-Sea-Ice

Creating sea ice maps of the Arctic and other polar regions
has remained a challenge for both research and industry; currently this
remains a manual interpretation task by experts in the field. Attempts
have been made to automate this process using neural networks like
CNNs. We expanded on previous work to automate this process by
utilizing a colorized image dataset of the Hudson Bay in Canada and a
SegFormer architecture to perform semantic segmentation prediction.
Our results indicate that the model performs significantly better than
a former attempt: we achieved an overall accuracy of 89% and a mean
IoU of 0.50 compared to a previous result using a standard U-Net model
with 83% and 0.44, respectively. While using this method is not accurate
enough to reliably implement in industry applications, it is a positive step
forward towards automating sea ice mapping.
