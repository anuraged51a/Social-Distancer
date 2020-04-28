# IBM CALL FOR CODE 2020

##The Problem:

The 2019–20 coronavirus pandemic is an ongoing pandemic of coronavirus disease 2019 (COVID-19) caused by severe acute respiratory syndrome coronavirus 2. To combat it, the world is embracing radical measures to flatten the curve like lockdowns and social distancing. But in various regions of our country, we have been seeing visible non-compliance of the strict lockdowns and social distancing norms which have been enforced by the government. So we can use Computer Vision to help answer questions such as: 
*Are people maintaining safe social distances?
*What surfaces are people touching that may need cleaning?
*How many people are wearing masks?


## The Solution: Social Distancer
We have made an AI tool to prevent spreading of coronavirus (COVID-19) by using computer vision on video surveillance. This is an all integrated social distancing analyzer AI tool which can be used to regulate social distancing protocol using video surveillance of CCTV cameras and drones.
Social Distancer automatically detects the extent to which social distancing protocols are followed in the area. Deploying it on current surveillance systems and drones used by police to monitor large areas can help to prevent coronavirus by allowing automated and better tracking of activities happening in the area. It shows analytics of the area in real-time. It can also be used to alert police in case of considerable violation of social distancing protocols in a particular area.
***
####The core features which we have been able to implement are:
- Get the real-time analytics
- Number of people in a particular area
- Number of people in high risk
- The extent of risk to a particular person.
- Doesn't collect any data of a particular person
- Stores a video output for review
 
## Future Improvements:
* Making it work with multiple cameras for particular object
* Auto-calibration 
* Faster processing

## Deploying:
`python social_distancing_analyser.py`

---
##Footnote

We have used YOLO V3 for implementing our solution. The main reasons for that are, YOLO looks at the whole image at test time so its predictions are informed by the global context in the image. It also makes predictions with a single network evaluation unlike systems like R-CNN which require thousands for a single image. This makes it extremely fast, more than 1000x faster than R-CNN and 100x faster than Fast R-CNN. 