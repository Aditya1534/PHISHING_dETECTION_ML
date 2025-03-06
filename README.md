# PHISHING_dETECTION_ML
🚀 Phishing Website Detection using LightGBM &amp; CatBoost
This project is a machine learning-based phishing detection system that outperforms traditional approaches, including those used by websites like PhishTank. Unlike PhishTank, which relies on manual reporting and blacklisting, this model automatically detects phishing websites with high accuracy by analyzing URL features.

🔹 Why is this better than PhishTank?
✅ Real-time detection – No need to wait for reports, the model detects phishing instantly.
✅ Detects new phishing sites – Works even if the phishing website is newly created and not in blacklists.
✅ Works on HTTPS sites too – Many phishing sites use https://, but this model can still detect them.

💡 How It Works

Uses LightGBM and CatBoost, which outperformed deep learning models like MLP.
Extracts domain, subdomain, TLD, and structural features of URLs.
Trained on a large phishing dataset, ensuring high generalization.
