# Fingerprint Authentication Web Demo

This is a simple frontend demo that uses **WebAuthn (Web Authentication API)** to allow users to register and login using their fingerprint or device's biometric feature.

##  Features

- Register user with email and username
- Create and store fingerprint credential (on browser)
- Login using fingerprint
- Displays list of registered users (on screen only)

## Technologies Used

- HTML5
- CSS (Bootstrap)
- JavaScript (WebAuthn API)

## 🧠 How It Works

1. User enters email and username, clicks "Register Fingerprint".
2. Browser asks for fingerprint/biometric access.
3. Credential is created and stored (temporarily in memory).
4. For login, user enters email and system verifies fingerprint.
5. Successful login shows confirmation.

## ⚠️ Limitations

- This demo does **not store** credentials permanently.
- No real backend — `/register-fingerprint` API call is just for structure (it needs to be built).
- Works only in supported browsers like **Chrome**, **Edge**, **Firefox** with biometric hardware.

## 📌 Setup Instructions (for demo only)

1. Open the HTML file in a browser that supports WebAuthn.
2. Register using your fingerprint.
3. Login with the same email to verify.
4. Refresh will clear data (as no backend exists).

##  TODO (for full project)

- Create backend using Node.js/Express or Django to store credentials securely.
- Use MongoDB or PostgreSQL for persistent user storage.
- Implement secure login and session handling.

##  Author

Made by [Your Name Here] as a WebAuthn learning project.


