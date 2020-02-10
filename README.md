# MULTIMODAL-EMOTION-RECOGNITION
*We have not published any work yet - so there is no discripancies regarding copyright.*      
This research work is focused on studying the capability of robots to understand human emotions in real-time. Understanding emotions will allow the systems to adapt according to the responses and behavioral patterns. If this happens in a reasonable sense of accuracy, then we would be expecting artificial agents to be our cognitive-consulting partners in our everyday life. Research would be extending in making the interaction more natural and responsive to sophisticated situations.  
Checkout this repository to know more about the dataset - https://github.com/SenticNet/MELD  
![MELD_about_data](https://github.com/ankurbhatia24/MULTIMODAL-EMOTION-RECOGNITION/blob/master/MELD.PNG)
## About the repository contents:
The /model directory contains the ipynb files of the baseline multimodal architecture which encorporates the video frames, text and the audio into a fused network as below.  
The video frames as concatenated in order to incorporate the temporal information, pretrained embeddings are used for conversion of word to vector in the text base model portion and mfcc features are convoluted forward from the audio.  
![baseline_multimodal](https://github.com/ankurbhatia24/MULTIMODAL-EMOTION-RECOGNITION/blob/master/Multimodal-architectures/baseline_model.png)  
The unimodel_text ipynb is the baseline text model provided in the SenticNet MELD paper.    
The /csv directory contains the csv files with the utterances, speakers, emotion, sentiment labels, etc.
  
## Incorporating the Context information
Skip connections and previous rememberance architectures are used for accurate emotion classification.  
*These details are not present in the repository. Will be added soon.*
