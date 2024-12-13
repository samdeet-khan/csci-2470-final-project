**Improving Student Retention: Deep Learning Strategies with Socioeconomic Data**


LINK TO PRESENTATION: https://docs.google.com/presentation/d/1RrigMwKeF5VwiSe2Pzp6J1I_iDnE4iazl2mIqenrBi0/edit?usp=sharing

LINK TO REPORT: https://docs.google.com/document/d/1ATTMwc3T3Xd3hc4nfUSzAtuogD80leEpTvC30IEmNb4/edit?usp=sharing

This project aimed to predict student dropouts using advanced deep learning models integrated with socioeconomic and demographic data. By leveraging Multi-Layer Perceptrons (MLPs) with embedding layers and TabTransformer architectures, the study analyzed a comprehensive dataset containing over 789,000 student records. The primary objective was to enhance predictive accuracy and provide actionable insights that educational institutions can use to implement early interventions, thereby improving student retention rates.

The dataset, sourced from BRAC’s Education Programme, includes a variety of features such as household income, parental educational attainment, and behavioral indicators. Extensive data preprocessing was conducted to handle missing values, encode categorical variables, and normalize numerical features, ensuring the data's suitability for deep learning models. Two distinct model architectures were developed and evaluated: an MLP enhanced with embedding layers and a TabTransformer model that utilizes transformer-based mechanisms to capture complex feature interactions. Both models were trained using weighted cross-entropy loss to address class imbalance and were evaluated based on F1-scores, ROC AUC, and confusion matrices.

The results indicate that the TabTransformer model negligibly outperforms the MLP with Embeddings, achieving an F1-score of 0.4342 compared to 0.4328. These findings demonstrate the effectiveness of both MLP embeddings and transformer-based architectures in modeling intricate relationships within socioeconomic data, providing reliable predictions for student dropouts. The project highlights the potential of deep learning in educational data mining and signals the potential for valuable tools that educators and policymakers can use to proactively identify and support at-risk students.

Acknowledgments
1. BRAC’s Monitoring and Evaluation Team: For providing access to the student dataset and supporting data-related efforts.
2. Brown University's Oscar GPU Cluster: For offering the necessary computational resources that facilitated efficient model training and experimentation.
3. Course Instructors and Peers: For valuable feedback and guidance throughout the project development process.

References: 
A comprehensive list of references is included in the project report, detailing all the academic papers and sources that informed this research.

Contact: 
For any questions or further information, please contact me at samdeet_khan@brown.edu
