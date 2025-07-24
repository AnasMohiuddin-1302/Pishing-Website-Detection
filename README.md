🔐 Phishing Website Detection
📌 Overview
This project is a Phishing Website Detection system using the Random Forest Classifier. It predicts whether a given website is legitimate or phishing based on various extracted features.

📊 Dataset Features
The dataset includes several features that help distinguish phishing websites from legitimate ones:

🌐 Have_IP
📧 Have_At
🔗 URL_Length
📏 URL_Depth
🔄 Redirection
🔒 https_Domain
🔽 TinyURL
➕ Prefix/Suffix
📡 DNS_Record
📈 Web_Traffic
⏳ Domain_Age
📆 Domain_End
🖼 iFrame
🖱 Mouse_Over
🛑 Right_Click
🚀 Web_Forwards
🛠 Requirements
Install the required dependencies:

pip install -r req.txt
🚀 Usage
1️⃣ Clone the Repository

git clone <repo_link>
cd phishing-website-detection
2️⃣ Install Dependencies

pip install -r req.txt
3️⃣ Run the Model

python predict.py
4️⃣ Deploy the App (if applicable)
If you have a Streamlit app:

streamlit run app.py
🏆 Model Details
🤖 Algorithm Used: Random Forest Classifier
🎯 Training Process: The model was trained on a dataset with an 80-20 train-test split.
📊 Performance Metrics: Evaluated using accuracy, precision, and recall.
🖼 App UI Screenshots
Here are some images showcasing the final application interface:
img1 Picture2 Picture3 Picture4

🤝 Contributing
Feel free to fork this repository and contribute! If you find any issues, open a pull request or create an issue.

📜 License
This project is licensed under the MIT License.

Let me know if you'd like any additional tweaks! 🚀🔍
