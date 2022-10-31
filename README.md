# Predicting customer age using computer vision
The project from the Computer Vision sprint of the Practicum DS course.

## Description
Here we have a dataset of photographs of people with their ages indicated. Our goal is to explore whether Data Science can help our supermarket chain detect underage people buying alcohol by building a model for verifying people's age from the photo.

First, we should do some EDA. Afterward, we could proceed to model development.

## Conclusion
After the EDA, we built a model to detect a person's age from the camera in the checkout area. Our model's mean absolute error is about 6, which is a pretty good result, but not for this particular task. With such an error, there would be many times when we won't detect an underage person correctly.    
Maybe we better try a different approach. For example, we could ask the person buying an alcoholic drink to show their ID to the camera. Then, reading the birth date from it would give a significantly accurate result.