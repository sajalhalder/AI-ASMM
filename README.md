# AI-ASMM : Artificial Intelligence to Automate Seagrass Morphology Measurement 

Seagrass meadows are an essential part of the Great Barrier Reef ecosystem, providing various benefits such as filtering nutrients and sediment, serving as a nursery for fish and shellfish, and capturing atmospheric carbon as blue carbon. Unfortunately, seagrass meadows are currently degraded in Australia. Seagrasses exhibit phenotypic plasticity, acclimating their morphology to environmental stressors, which can act as an early warning of the possible risk of larger-scale seagrass loss. Morphological changes can also affect the delivery of ecosystem services such as carbon sequestration. Measuring seagrass growth by measuring morphological parameters such as the length and width of leaves, rhizomes, and roots is essential. However, the manual process of measuring morphological parameters of seagrass can be time-consuming, inaccurate and costly, so researchers are exploring machine-learning techniques to automate the process. To automate this process, researchers have developed a machine learning model that utilizes image processing and artificial intelligence to measure morphological parameters from digital imagery. The study uses a deep learning model called YOLO-v6 to classify three distinct seagrass object types and determine their dimensions. The results suggest that the proposed model is highly effective, with an average recall of 97.5%, an average precision of 83.7%, and an average F1 score of 90.1%.

To implement this code we modified publicly available YOLO-v6 model. If you want to use the code in your research work please cite YOLO-v6 and the following paper.

Sajal Halder, Nahina Islam, Biplob Ray, Emma Jackson, Pushpika Hettiarachchi, Elizabeth Andrews. " Artificial Intelligence to Automate Seagrass Morphology Measurement" 
Submitted to Journal of Environmental Management, 2024.

In this research work, our main contributions are as follows. 

  (i) We constructed an annotated dataset of seagrass objects, employing the image annotation platform Roboflow, renowned for its efficiency.

  (ii) We devised a seagrass object classification model using advanced deep learning techniques, effectively detecting the three distinct object categories.
    
  (iii) We introduced a dynamic model tailored for quantifying object morphology, encompassing dimensions such as height and width.
    
  (iv) Analysis of our experimental results underscores the efficacy of our model, with an average recall of 97.5%, average precision of 83.3%, and an average F1-score of 90.1%.
    
  (v) Significantly, our developed morphology calculator achieves an accuracy rate of 78.14% when measuring the heights of the three longest objects. 

