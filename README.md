# 🚗 SpareHub - Auto Spare Parts Marketplace

SpareHub is a B2B platform designed to connect car and bike spare parts **manufacturers** and **retailers**. It enables efficient inventory management, product listing, and ordering — all in one place.

---

## 🖼️ Project Preview

<img src="assets/preview.png" alt="SpareHub Screenshot" width="100%" />




[spare-hub-presentation.pptx](https://github.com/user-attachments/files/21203108/spare-hub-presentation.pptx)

> Replace `assets/preview.png` with your actual image path.

---

## 🧰 Tech Stack

| Technology   | Description                |
|--------------|----------------------------|
| 🐍 Django     | Backend / REST APIs        |
| 🐦 Flutter    | Android/iOS Frontend       |
| 🐬 MySQL      | Relational Database        |
| 🔐 JWT        | Authentication System      |
| 🔧 Git        | Version Control            |

---

## ✨ Features

- 👥 Manufacturer and Shop Logins
- 📦 Product Listing & Categorization
- 🔎 Real-time Search & Filters
- 🛒 Add to Cart and Order Requests
- 🔐 Secure Login/Signup with JWT
- 📈 Dashboard for Sales and Stock Analytics

---

## 📥 Installation Guide

### 🖥️ Backend (Django)
```bash
git clone https://github.com/your-username/sparehub-backend.git
cd sparehub-backend
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

---

## 📱 Download the App

After each successful deployment, the latest APK is available for download:

[![Download Android APK](https://img.shields.io/badge/Download-Android%20APK-green?logo=android)](https://github.com/farmansunasara/sparehub-b2b-platform/releases/latest/download/app-release.apk)

> **Automatic Release Process:**  
> APKs are automatically built and attached to GitHub Releases whenever a version tag (e.g., `v1.0.0`) is pushed to the repository. The release workflow builds the Flutter app in release mode and uploads the APK as a release asset.
>
> You can always find the latest version in the [Releases](https://github.com/farmansunasara/sparehub-b2b-platform/releases) section.

### 🔨 Manual APK Build

If you need to build the APK manually:

```bash
# Navigate to the Flutter app directory
cd sparehubapps

# Get dependencies
flutter pub get

# Build the APK in release mode
flutter build apk --release

# The APK will be available at:
# sparehubapps/build/app/outputs/flutter-apk/app-release.apk
```

To manually upload the APK to a GitHub Release:
1. Create a new release on GitHub with a version tag (e.g., `v1.0.0`)
2. Upload the APK file from `sparehubapps/build/app/outputs/flutter-apk/app-release.apk` as a release asset
3. Publish the release

---

## 🚀 Live Demo

- **Backend API:** [https://your-backend.onrender.com](https://your-backend.onrender.com)
- **Demo Account:**
  - Username: `demo_user`
  - Password: `demo_pass`

---

## 📚 API Documentation

API docs available at: [https://your-backend.onrender.com/api/docs/](https://your-backend.onrender.com/api/docs/)

---

## ⚙️ Environment Variables

| Variable         | Description                  |
|------------------|------------------------------|
| `DATABASE_URL`   | PostgreSQL connection string |
| `SECRET_KEY`     | Django secret key            |
| `DEBUG`          | Django debug mode            |
| `ALLOWED_HOSTS`  | Allowed hosts for Django     |
| `EMAIL_HOST`     | SMTP server                  |
| ...              | ...                          |

---

## 🤝 Contributing

Contributions are welcome! Please open an issue or submit a pull request.

---

## 🛠️ Deployment

To deploy on Render:
1. Fork and clone this repo.
2. Set up environment variables as above.
3. Push to your Render-connected repo.
4. Render will auto-deploy using the provided `render.yaml` and `ci-cd.yml`.

---

## 🧪 CI/CD Status

![CI/CD](https://github.com/farmansunasara/sparehub-b2b-platform/actions/workflows/ci-cd.yml/badge.svg)

---

## 📸 Screenshots

<!-- Add more screenshots or GIFs here -->

---

## 📅 Roadmap

- [ ] iOS app build & release
- [ ] Multi-language support
- [ ] Advanced analytics dashboard
- [ ] ...

---

## 📝 License

This project is licensed under the MIT License.

---

## 📬 Contact

For support or business inquiries, contact [your-email@example.com](mailto:your-email@example.com)

---
