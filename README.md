
# BloxAuth

**BloxAuth** is a cutting-edge authentication system that leverages PGP (Pretty Good Privacy) for secure logins and integrates Passkeys (WebAuthn) for a seamless, passwordless experience. Designed for modern web applications, BloxAuth provides robust security features while ensuring a smooth user experience.

## Features

- **PGP Authentication**: Secure login using PGP public keys.
- **Passkeys (WebAuthn)**: Passwordless authentication using the latest WebAuthn standard.
- **Secure Storage**: Safeguard user data with industry-standard encryption.
- **Cross-Platform**: Compatible with all major browsers and platforms.
- **Scalable Architecture**: Built with Node.js and Express for scalable backend support.
- **Easy Integration**: Simple API and modular design for easy integration into existing projects.

## Directory Structure

```
auth-app/
│
├── backend/
│   ├── controllers/
│   │   ├── authController.js
│   ├── models/
│   │   ├── userModel.js
│   ├── routes/
│   │   ├── authRoutes.js
│   ├── utils/
│   │   ├── pgpUtils.js
│   │   ├── webAuthnUtils.js
│   ├── app.js
│   ├── config.js
│   ├── server.js
│
├── frontend/
│   ├── css/
│   │   ├── styles.css
│   ├── js/
│   │   ├── auth.js
│   ├── index.html
│
├── tests/
│   ├── backend/
│   │   ├── authController.test.js
│   │   ├── pgpUtils.test.js
│   │   ├── webAuthnUtils.test.js
│   ├── frontend/
│   │   ├── auth.test.js
│
├── .gitignore
├── package.json
├── README.md
```

## Getting Started

### Prerequisites

- **Node.js** (v14+)
- **npm** (v6+)

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/bloxauth.git
   cd bloxauth
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Start the server**:
   ```bash
   npm start
   ```

### Usage

1. **Frontend**:
   - Open `frontend/index.html` in your browser.
   - Enter your PGP public key or use a passkey to log in.

2. **Backend**:
   - API endpoints for authentication are available at `http://localhost:3000/api`.

