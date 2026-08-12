# Walar

Walar is a web-based platform built around the W Commonwealth ecosystem. It provides a unified interface for account access, messaging, media, and wallet-related functionality.

## ✨ Features

* 🔐 **Authentication** — User registration and sign-in
* 💬 **Inbox & Communication** — Messaging interface
* 📞 **Calls** — Dedicated calling interface
* 💳 **Wallet** — Cryptocurrency wallet interface with Solana support
* 🪙 **Tokens** — Token-related functionality
* 🎬 **Movies** — Media and movie interface
* 🔒 **Encryption** — Dedicated encryption interface
* 🌐 **Web-based** — Runs directly in a modern browser
* 📱 **Responsive UI** — Designed for desktop and mobile

## 🌐 Website

**Walar:** https://walar.xyz

## 🛠️ Tech Stack

Walar currently uses:

* HTML5
* CSS3
* Vanilla JavaScript
* Browser Web APIs
* REST API endpoints

The frontend does not require a JavaScript framework or build system.

## 📁 Project Structure

```text
.
├── index.html       # Authentication / landing page
├── main.html        # Main Walar interface
├── wallet.html      # Wallet interface
├── token.html       # Token interface
├── inbox.html       # Messaging / inbox interface
├── call.html        # Calling interface
├── encrypt.html     # Encryption interface
├── movies.html      # Media / movie interface
├── WLR_Logo.png     # W Commonwealth logo
├── walar_icon.png   # Walar icon
├── solana.png       # Solana asset
└── CNAME            # Custom domain configuration
```

## 🚀 Running Locally

Because Walar is a static web application, it can be served using any basic HTTP server.

For example, with Python:

```bash
python -m http.server 8080
```

Then open:

```text
http://localhost:8080
```

Some functionality depends on the Walar API and may not work correctly when the project is run completely offline.

## 🔌 API

The frontend communicates with the Walar backend through:

```text
https://api.walar.xyz
https://api2.walar.xyz
```

The second endpoint is used as a fallback when the primary API is unavailable.

## ⚠️ Security Notice

Walar handles authentication and wallet-related functionality. Do not use real funds, credentials, private keys, or other sensitive information with an untrusted or modified copy of the software.

Always verify that you are using the official Walar website and trusted software before entering sensitive information.

## 🤝 Contributing

Contributions, bug reports, and suggestions are welcome.

1. Fork the repository.
2. Create a branch for your changes.
3. Make and test your changes.
4. Open a pull request with a clear description of your changes.

## 📄 License

Walar is licensed under the **MIT License**. See [`LICENSE`](LICENSE) for the full license text.

## 🔗 Links

* Website: https://walar.xyz
* Repository: https://github.com/WCommonwealth/walar
