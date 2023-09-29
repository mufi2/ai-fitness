# AI Fitness Tracker Project
### Exploring the Integration of Context-Aware Applications in Strength Training

This notebook presents a comprehensive analysis of the application of context-aware systems in strength training, showcasing the development, implementation, and evaluation of models designed to enhance exercise tracking and analysis.

## Abstract

The study encapsulates the innovative exploration of context-aware applications in the realm of strength training. Utilizing data from wristband accelerometers and gyroscopes, the research unveils models adept at monitoring exercises, enumerating repetitions, and identifying incorrect forms. The models' precision and efficiency echo the insights offered by human personal trainers, marking a significant stride in automated exercise tracking and analysis.

## Introduction

![Screenshot 2023-09-29 203605](https://github.com/mufi2/ai-fitness/assets/120253718/2bae63e0-2ef0-49af-b969-24343829dc56)


### Background
In the contemporary era, the fusion of artificial intelligence and fitness has unveiled new horizons for exercise tracking and analysis. This study is anchored in the exploration of context-aware applications, specifically in the domain of strength training. The focus is cast on the intricate analysis of data derived from wristband accelerometers and gyroscopes, aiming to foster an automated, precise, and efficient mechanism for exercise tracking.

### Problem Statement
The prevailing landscape of exercise tracking is predominantly manual, with a conspicuous absence of automated mechanisms adept at tracking free weight exercises with precision. This study seeks to bridge this gap, introducing models that not only track but also analyze and offer insights into the exercises.

### Objectives
- To develop and evaluate models capable of automated exercise tracking and analysis.
- To assess the precision and efficiency of the models in real-time exercise monitoring.
- To explore the potential of integrating these models into mainstream fitness tracking applications.

### Significance
The research stands as a contribution to the burgeoning field of artificial intelligence in human activity monitoring, offering insights and models that could potentially revolutionize exercise tracking, making it more automated, precise, and insightful.

## Methodology

### Research Design
The study adopts a supervised learning approach, leveraging MbientLab’s wristband sensor research kit for comprehensive data collection. A meticulous process of data gathering, preprocessing, model development, and evaluation is followed to ensure the accuracy and reliability of the findings.

### Data Collection
Data is amassed from five participants engaged in barbell exercises. The wristband’s accelerometer and gyroscope sensors, set at default settings, serve as the primary data collection tools, capturing intricate details of the participants’ movements and exercises.

![Screenshot 2023-09-29 204130](https://github.com/mufi2/ai-fitness/assets/120253718/2fe5dc0b-72b0-4f68-9db8-393c8eddcd88)

![Screenshot 2023-09-29 204317](https://github.com/mufi2/ai-fitness/assets/120253718/c04888d2-57bd-4e1a-abb8-5909b953e415)

![Screenshot 2023-09-29 204518](https://github.com/mufi2/ai-fitness/assets/120253718/d4b7be25-abab-4cf4-878d-87cbb96a82ef)

### Data Analysis
The study evaluates a spectrum of machine learning algorithms, including Neural Network, Random Forest, Support Vector Machine, K-nearest Neighbours, Decision Tree, and Naive Bayes. The algorithms are assessed based on their accuracy, efficiency, and real-time data processing capabilities.


### Validation
A leave-one-out method is employed for model training and testing. This approach ensures a comprehensive evaluation, leading to an average accuracy of 85.43%, indicative of the models’ reliability in exercise tracking and analysis.

### Features
The research underscores the significance of features like pca 1, acc y, pca 3, gyr x temp std ws 4, and acc r pse in enhancing the predictive power of the machine learning models.

![Screenshot 2023-09-29 204618](https://github.com/mufi2/ai-fitness/assets/120253718/7c9b0caa-b37c-4070-9ca9-8cb1e37319cb)
![Screenshot 2023-09-29 204730](https://github.com/mufi2/ai-fitness/assets/120253718/47acb6cf-6b70-4135-b1bb-31fbdb9941df)

## Results and Discussion
![Screenshot 2023-09-29 204926](https://github.com/mufi2/ai-fitness/assets/120253718/3b0f69c2-64c4-4744-92ca-36b869b9a78e)
![Screenshot 2023-09-29 205003](https://github.com/mufi2/ai-fitness/assets/120253718/c090b834-8b84-4a8c-ae8d-01d4d9f4fccc)
![Screenshot 2023-09-29 204950](https://github.com/mufi2/ai-fitness/assets/120253718/484b95ce-b1a8-4510-82f1-908c4314cdb2)


### Findings
The comparative analysis of machine learning algorithms reveals their distinct capabilities in exercise tracking and analysis. The models exhibit a commendable accuracy, with real-time data processing emerging as a pivotal aspect of their performance.

### Comparative Analysis
The models are evaluated and compared, shedding light on their individual and collective strengths and areas for improvement. The insights derived are instrumental in understanding the potential integration of these models into mainstream fitness applications.

### Implications
The findings of the study bear significant implications for the field of AI in fitness. The models’ precision, efficiency, and real-time data processing capabilities underscore the potential transformation of exercise tracking, making it more automated and insightful.

![Screenshot 2023-09-29 205515](https://github.com/mufi2/ai-fitness/assets/120253718/d2ab535a-94d5-40aa-85d6-691ea6a99318)

## Conclusion

The study illuminates the transformative potential of integrating artificial intelligence into fitness tracking. The developed models, characterized by their accuracy, efficiency, and real-time data processing, stand as testament to the advancements in automated exercise tracking. The findings not only contribute to the existing body of knowledge but also pave the way for future innovations, where exercise tracking transcends manual boundaries, becoming more automated, precise, and insightful.

### Recommendations
- Further research to enhance the accuracy and efficiency of the models.
- Exploration of advanced AI algorithms to bolster real-time data processing.
- Integration of context-aware applications to offer personalized exercise insights and recommendations.
