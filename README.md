# ceramic-semantic-segmentation-code
Visual inspection systems in industries have increasingly gained a lot of interests. 
Advances in manufacturing activities have led to mass production in order to reduce overall operational cost. 
The visual inspection systems provide instant quantitative feedback such as quantity and type of defects. 
In this section, we present a visual inspection method of tiles industry using a deep learning approach. 
The deep learning approach is employed for segmenting cracks and backgrounds in tiles. 
Due to the small size of the cracks, image segmentation is crucial. 
Architecture for segmenting semantic objects in a color image is the main inspiration to be applied on this paper. 
Semantic segmentation is widely applied for image analysis in the real world, one  of  which is to conduct 
a visual inspection of tile surfaces where each pixel input of high-resolution images is categorized into 
a set of semantic labels. In order to test the performance of the segmentation algorithm, 
SegNet  architecture  with the DeepLabV3plus were compared. A new dataset named UBIN 
is also proposed as a training and evaluation data. The training data that we have collected 
shows promising results on visual inspection when using the proposed algorithm. 
We believe that this work could improve to a more advanced manufacturing industries.

![Image of IO](IO.png)

**Input RGB Image from UBIN dataset and Output Ground Truth based on  Class  label.  The  Background  class  is  segmented  using  blue  color,  while the crack class is segmented using brown color**