# summer-2021-Image-Caption-LDA

## Abstract 
COVID-19 has disrupted urban life in many different ways. To control the spread of the pandemic, social distancing has been mandated by state and city governments per the recommendations of public health officials. The compliance level among the public regarding such mandates is crucial to effectively slow down or stop the spread. The public activity of pedestrians in the street during the‘stay-at-home’ order is an approximation of ‘urban living’ under theconstraints of such mandates. However, the degree of complianceis hard to measure without explicit input from the pedestriansthemselves. As different areas of urban locations such as New York City experiences a varied level of the virus spread, several questions emerge.
**How have social distancing mandates influenced the activities and life in the city?**
**How did life in the city changeduring different phases of the pandemic?**

## What We Are Doing
In this project, we take a computational perspective to answer these questions and understand urban heartbeat during COVID-19.Towards that end, we use the information on the public activityon the street level gathered through video footage from cameras instrumented on ride-sharing vehicles throughout the city

## Our Method 
By combining computer vision and natural language processingtechniques, we develop a language model to provide a semanticdescription of an image to understand the public activities presentin the scene. This is achieved based on a **vision-language model** trained on a publicly available dataset and then fine-tuned on our labeled dataset. We use our trained model to generate semanti-cally coherent image descriptions and filter out the words thatare specific to public activities outlining the actor, action, and lo-cation (who, what, where). By modeling the word distributionsthrough topic modeling techniques such as **Latent Dirichlet Dis-tribution (LDA)**, we identify salient themes in neighborhoodsover a specific period through topic modeling and compare topicdistributions to detect changes over time. 

## Methods Explanation
