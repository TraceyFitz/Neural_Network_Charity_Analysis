# Neural_Network_Charity_Analysis

The purpose of this analysis is to determine which organizations receiving funding from Alphabet Soup are sucessful. The goal is provide funding to only organizations that have a good chance of success and eliminate wasted funding provided to organizations who are unlikely to succeed. 



Unfortunately I was not able to optimiza my model and achieve over 75% accuracy. My first model had an accuracy of 70% <img width="1680" alt="First Pass - Most accurate " src="https://user-images.githubusercontent.com/97544078/177423631-4e0ef3ee-af2d-4a4d-88f6-c51c02dd41c6.png">

In an attempt to optimize and increase accuracy, I tried removing NAME, keeping only EIN. Then I added another layer, which reduced the accuracy to in the 40% range. Then I tried changing the activation function from relu to sigmoid, which also reduced the accuracy, although by slightly less than the first change to 53% range. <img width="1680" alt="Reduced Accuracy " src="https://user-images.githubusercontent.com/97544078/177423260-b86859b8-8647-4dfe-9c08-fe6667878aa0.png">
