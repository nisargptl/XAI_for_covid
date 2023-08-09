# XAI_for_covid
Contains code and example images developed during our research project. Our paper can be found at https://link.springer.com/chapter/10.1007/978-3-031-31417-9_38

# Explainable AI
According to Wikipedia, Explainable AI (XAI), also known as Interpretable AI, or Explainable Machine Learning (XML), is artificial intelligence (AI) in which humans can understand the reasoning behind decisions or predictions made by the AI. XAI is important, more so in the medical domain because it helps us gain trust on the black-box models, which are hard to describe. Nowadays, many deep learning models can be trained to achieve higher accuracies for various tasks, but for some models, it also becomes hard to explain how the model is arriving at a particular decision. Due to this reason, we set out to implement different available XAI techniques on the models trained to categorize covid, normal and viral pneumonia cases from chest x-ray images which attempt to explain the results of Resnet18 and Resnet50. The results were then shown to the domain experts and qualitative and quantitative feedback was taken which we have compiled in our paper.
# Process overview
![alttext](https://github.com/nisargptl/XAI_for_covid/blob/main/images/process_overview.png)

# Let's now see detailed images for each of the categories.
As you will see, different techniques have highlighted different areas with different color grading in the images. These techniques attempt to mark the areas that it feels are important for the model to make a decision. The color scale is also shown which tells us if the areas affected positively or negetively in the decision making. Detailed explanations can be found in our paper.
# 1) Covid
![alttext](https://github.com/nisargptl/XAI_for_covid/blob/main/images/covid_gradcams.png)
![alttext](https://github.com/nisargptl/XAI_for_covid/blob/main/images/covid_captum.png)

# 2) Normal
![alttext](https://github.com/nisargptl/XAI_for_covid/blob/main/images/normal_gradcams.png)
![alttext](https://github.com/nisargptl/XAI_for_covid/blob/main/images/normal_captum.png)

# 3) Viral Pneumonia
![alttext](https://github.com/nisargptl/XAI_for_covid/blob/main/images/viral_gradcams.png)
![alttext](https://github.com/nisargptl/XAI_for_covid/blob/main/images/viral_captum.png)
