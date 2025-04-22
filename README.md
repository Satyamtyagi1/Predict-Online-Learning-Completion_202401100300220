📊 Predicting Online Learning Completion
This project uses machine learning to predict whether a learner will complete an online course based on their activity logs. It implements a Gradient Boosting Classifier trained on engagement features like videos watched, assignments submitted, and forum participation.

🚀 Project Overview
Online learning platforms often face high dropout rates. This model helps identify learners who are at risk of not completing a course, enabling early interventions to improve retention.

Features Used:
videos_watched

assignments_submitted

forum_posts

Target Variable:
completed (Yes/No, encoded as 1/0)

🧠 Technologies Used
Python 3.x

pandas

scikit-learn

matplotlib

seaborn

📝 How It Works
Load and preprocess the dataset

Encode categorical labels

Split the data into training and testing sets

Handle class imbalance with weighted samples

Train a Gradient Boosting Classifier

Evaluate performance with accuracy, classification report, and confusion matrix

📈 Example Output
Accuracy Score

Precision / Recall / F1-Score

Confusion Matrix Visualization

📂 Dataset
The dataset online_learning.csv should contain at least the following columns:


videos_watched	assignments_submitted	 forum_posts	completed

Note: The completed column must contain values like "yes" and "no".

🔧 How to Run
bash
Copy
Edit
# Install dependencies
pip install pandas scikit-learn matplotlib seaborn

# Run the script
python predict_completion.py
📄 License
This project is open-source and available under the MIT License.

🙌 Acknowledgements
Scikit-learn team for the machine learning tools

Matplotlib and Seaborn for visualizations

Open educational datasets for inspiration
