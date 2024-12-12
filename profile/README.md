# ![Logo Anggarin](https://github.com/user-attachments/assets/8a6f2ad2-2fc6-4bd4-ba68-c6674edd655b)

# ANGGAR.IN PROJECT DOCUMENTATION

## Team Profile

### Team ID : C242-PS048

### These Are Our Team Members :

* (ML) M312B4KY2530 - Mochammad Dhiya Ulhaq - Universitas Sebelas Maret
* (ML) M312B4KY2631 - Muhamad Faqih Zacky - Universitas Sebelas Maret
* (ML) M312B4KX3214 - Nadya Putri Uswatun Hasanah - Universitas Sebelas Maret
* (CC) C214B4KY2719 - Muhammad Alvanditya Sasongko - Universitas Islam Indonesia
* (CC) C312B4KY4470 - Whilyan Pratama - Universitas Sebelas Maret
* (MD) A783B4KX1433 - Fathiya Salsabila - Institut Teknologi Sains dan Kesehatan PKU Muhammadiyah Surakarta
* (MD) A133B4KY2721 - Muhammad Alvin Nugraha Sujana - Politeknik Negeri Samarinda

### Roles

**Machine Learning:**
* Stock Recommendation (Financial Freedom Calculator) - Mochammad Dhiya Ulhaq (M312B4KY2530) & Nadya Putri Uswatun Hasanah (M312B4KX3214)
* Stock Prediction (Financial Freedom Calculator) - Mochammad Dhiya Ulhaq (M312B4KY2530) & Nadya Putri Uswatun Hasanah (M312B4KX3214)
* Receipt OCR (Income and Expense Tracking) - Muhamad Faqih Zacky (M312B4KY2631)
* Audio Recognition (Income and Expense Tracking) - Muhamad Faqih Zacky (M312B4KY2631)

**Cloud Computing:** 
>>EDIT TEKS DIBAWAH INI DENGAN ROLE CC

**Mobile Development:**
>>EDIT TEKS DIBAWAH INI DENGAN MD

# Anggar.In Cloud Computing Project Explanation
This project is our final project for Google Bangkit Academy 2024 Batch 2.

**Project Background:**

Financial stability is crucial for personal and societal well-being, yet many Indonesians face challenges in achieving it. Data from BPS and a 2023 DBS survey indicate a large portion of household income is spent on non-essential items without proper planning. This issue is compounded by low financial literacy, leading to unnecessary spending and limiting the ability to save. If left unaddressed, these problems may prolong financial instability and negatively affect the quality of life in Indonesia.

To tackle this issue, our team developed Anggar.In, a comprehensive financial management solution. The app helps users track income and expenses through manual input, receipt scanning, and voice commands, offering a clear view of spending patterns. Its personalized budgeting feature aids in managing spending limits, while savings goal planning supports consistent savings. Anggar.In also provides financial analysis tools, presenting spending trends and insights to help users become more aware of their finances. The investment recommendation system can also guide users towards financial freedom.

Leveraging machine learning, cloud computing, and mobile technology, Anggar.In aims to boost financial awareness, foster sustainable habits, and support informed decision-making, helping Indonesians navigate economic challenges and build long-term financial resilience.

**Machine Learning:** 

In the Machine Learning path, we developed several features, starting with our MVP [stock prediction](https://github.com/Anggar-In/Machine-Learning/tree/main/stock_price_predictions) and [recommendation models](https://github.com/Anggar-In/Machine-Learning/tree/main/stockRecommendation) for a financial freedom calculator. These models utilize TensorFlow, are saved using TensorFlow.js for web deployment, preprocess data using Min-Max Scaler for normalization, and apply time series forecasting for stock price prediction alongside linear regression for stock recommendations. Beyond the MVP, we also building supplementary features beyond the MVP, such as [Receipt OCR](https://github.com/Anggar-In/Machine-Learning/tree/main/Receipt_OCR) and [Audio Recognition](https://github.com/Anggar-In/Machine-Learning/tree/main/AudioRecognition). The Receipt OCR leverages the Pytesseract library for extracting text from images, while the Audio Recognition feature utilizes the WebSpeech API. Both systems are tuned with preprocessing techniques for image or audio and use regex for data extraction. This feature is useful for automating expense and income tracking.

**Cloud Computing:** 

In this capstone project, the cloud computing division plans to create a backend and cloud computing design using Node.js as API and Google Cloud to deploy the API and database. We initially planned to use cloud storage to store OCR results, cloud functions to run the API, Firestore as a NoSQL database, Compute Engine for ML computing, Cloud IAM to set up access to Google Cloud, Vertex AI to deploy and train ML, and the Google Cloud pricing calculator to estimate project costs. However, in the implementation, we didn't use everything as planned because using some services was sufficient.

**Mobile Development:** 

>>EDIT TEKS DIBAWAH INI DENGAN BACKGROUNDER MOBILE DEVELOPMENT DI PROJECT BRIEF

# How to Use The Code
* [Anggar.In Machine Learning Repository](https://github.com/Anggar-In/Machine-Learning)
* [Anggar.In Cloud Computing Repository](https://github.com/Anggar-In/Cloud-Computing)
* [Anggar.In Mobile Developments Repository](https://github.com/Anggar-In/Mobile-Development)
