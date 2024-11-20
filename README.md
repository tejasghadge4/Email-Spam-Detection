# Email Spam Detection using Logistic Regression

Email spam detection is a crucial task in modern communication systems to distinguish between legitimate (ham) and unwanted (spam) messages. This project focuses on building a machine learning model using Logistic Regression to classify emails as spam or ham effectively. The primary objective is to reduce the number of unwanted messages that reach users' inboxes while ensuring legitimate emails are not flagged incorrectly.

The dataset used for this project consists of 5,572 labeled email entries. Each entry contains a Category column, indicating whether the email is spam or ham, and a Message column containing the email's text. To prepare the data, the Category labels were converted to binary values (ham=0 and spam=1). The text data was then vectorized using the TF-IDF (Term Frequency-Inverse Document Frequency) technique to transform the email content into numerical features suitable for machine learning algorithms.

Logistic Regression was chosen for its simplicity and effectiveness in binary classification tasks. After splitting the data into training and testing sets, the model was trained and evaluated. The model achieved a high accuracy of 96.53%, indicating its effectiveness in distinguishing between spam and ham emails. A confusion matrix was generated to further analyze performance, showing that the model correctly identified 1,448 ham emails and 166 spam emails. However, it misclassified 58 spam emails as ham. The precision for spam detection was excellent at 100%, but the recall was 74%, highlighting areas for potential improvement.

To visualize the model’s performance, a heatmap of the confusion matrix was created. This visualization effectively illustrates true positives, true negatives, false positives, and false negatives, providing insights into the model’s strengths and weaknesses. The project demonstrates the practical application of machine learning in filtering spam messages, a critical feature for email service providers, customer support platforms, and corporate communication systems.

Future improvements could include addressing class imbalance using techniques like SMOTE (Synthetic Minority Oversampling Technique), which may improve recall for spam messages. Additionally, experimenting with advanced algorithms such as Random Forests or Neural Networks could further enhance the model’s performance. Incorporating email metadata, such as sender and subject information, could also provide more robust predictions.

This project serves as a foundational step toward developing an efficient spam detection system, showcasing the potential of machine learning in real-world applications.






