# 🌟 **AdhariFy** 🌟

![AdhariFy Logo](static/images/lag.png)

🚀 **AdhariFy** is an innovative liveness detection platform, developed as part of the prestigious **Smart India Hackathon (SIH)** by Team **DarkBeast**. Our goal is to revolutionize identity verification, making it more secure, reliable, and user-friendly. Say goodbye to spoofing and hello to AdhariFy!

## 🔥 **Why AdhariFy?**

In an era where digital security is paramount, **AdhariFy** stands out as a game-changer. Here’s why:

- **🛡️ Enhanced Security:** Our liveness detection technology ensures that only real, live users can authenticate their identity, reducing the risk of fraud.
- **💡 Intelligent Detection:** Using advanced machine learning algorithms, AdhariFy can differentiate between live users and spoofing attempts with high accuracy.
- **⚡ Fast & Efficient:** The platform provides real-time liveness detection, ensuring seamless user experience without compromising on security.
- **🌍 Versatile Applications:** AdhariFy is adaptable across various domains, making it the go-to solution for multiple industries.

## 🚀 **Use Cases & Practical Applications**

### 1. **E-Governance**
   - **Aadhaar Verification**: Ensure the person verifying their identity via Aadhaar is genuinely present, reducing identity theft.
   - **Online Voting Systems**: Enable secure and tamper-proof online voting, ensuring the voter is physically present.

### 2. **Banking & Finance**
   - **Digital Onboarding**: Verify the identity of new customers during digital onboarding to prevent fraudulent account creation.
   - **Transaction Authentication**: Add an extra layer of security to financial transactions by verifying the user’s presence during high-value operations.

### 3. **Healthcare**
   - **Telemedicine**: Ensure that the person consulting with a healthcare provider online is indeed the patient, protecting sensitive medical data.
   - **Insurance Claims**: Authenticate the presence of a claimant during video-based insurance claims processing.

### 4. **E-Commerce**
   - **Secure Purchases**: Protect online shoppers by verifying the user’s identity during high-value purchases or account changes.

## 🔧 **Project Structure**

Here’s a quick overview of the project structure:

```
AdhariFy/
│
├── static/
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   └── liveness.js
│   └── images/
│       ├── lag.png
│       └── aadhar.svg
│
├── templates/
│   ├── index.html
│   └── about.html
│
├── app.py
├── README.md
└── requirements.txt
---

## 🚀 Features

- **Real-time Face Detection** 🧑‍💻
- **Liveness Detection** using facial landmarks 👁️👁️
- **Simple and Intuitive UI** 🎨
- **Secure and Fast** 🛡️⚡

## 🎯 How It Works

- The application captures real-time video from the webcam.
- It uses OpenCV and Haar cascades to detect faces and eyes in the video feed.
- A simple liveness check is performed by ensuring that both eyes are detected in the frame.
- If liveness is detected, a green bounding box with "Liveness Detected" is shown. Otherwise, it indicates "Spoof Detected" with a red bounding box.

## 📸 Screenshots

| Liveness Detected | Spoof Detected |
|-------------------|----------------|
| ![Liveness Detected](static/images/liveness_detected.png) | ![Spoof Detected](static/images/spoof_detected.png) |

## 🌟 Contribution

Contributions are welcome! Feel free to open an issue or submit a pull request. 😊

## 💬 Contact

Feel free to reach out for any inquiries or suggestions!

- **Email**: [koushiksarkar741777@gmail.com](mailto:koushiksarkar741777@gmail.com)
- **GitHub**: https://github.com/

*Happy Coding!* 😄🚀
