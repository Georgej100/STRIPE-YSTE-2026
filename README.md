# STRIPE-YSTE-2026
An Investigation into the Impact of Training Data Variations on Accuracy and reliability in Machine Learning Models

## Abstract
In 3 years, LLMs have become widely accessible to the public. More AI generated texts, videos and images are appearing online. AI companies use internet scrapers to collect vast amounts of data for machine learning.  I investigated how variations in composition and quality of AI training data can influence the factuality and accuracy of the model. More specifically the following questions:
How gaps/missing data from training data can affect a model’s ability to provide a factual output.
How AI generated information in a dataset can affect the accuracy and reliability of a model.
I carried out 2 experiments that used fine-tuning to simulate training on a smaller scale. In test 1, a model was fine tuned on a dataset with a gap in its knowledge. Its performance was compared against a control model to see the performance loss. Results show minimal performance differences between control and variant models on a large dataset, but on a reduced dataset, there was losses of upto 12% and higher.
In test 2, I simulate a phenomenon called model collapse. This is when a model is recursively trained on AI generated training data, causing the model’s performance to degrade as more iterations were done. In my simulation of this, I did not see this phenomenon. I came to the conclusion that without the randomness and noise found on the internet, model collapse wouldn't happen. However the model did create extra data, showing us the summarisation model was creating new, unchecked data.
My project highlights the need for screening AI training data and ensure data quality is the highest it can be.

## Contents
- Project Book (pdf)
- Project Diary (pdf)
- Code (.ipynb)

