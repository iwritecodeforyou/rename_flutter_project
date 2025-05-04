## 🔄 flutter\_brand – Automate Flutter Project Renaming in 2 Minutes

A one-command Bash script that **renames your Flutter project** in seconds — including app name, package ID, app label, Dart imports, and launcher icon.

### 🚀 Features

* 🔁 Rename project in `pubspec.yaml`
* 📦 Change Android/iOS package name (via `change_app_package_name`)
* 📂 Update all Dart import paths
* 🎨 Replace and regenerate app icons (via `flutter_launcher_icons`)
* 🧹 Clean backup and temp files

### ⚙️ How to Use

1. Drop `setup_branding.sh` into your Flutter project root.
2. Run using Git Bash (Windows) or terminal (macOS/Linux):

```bash
./setup_branding.sh
```

3. Follow the prompts to:

   * Enter new app name (snake\_case)
   * Enter new package name (e.g. `com.example.newapp`)
   * Optionally provide a PNG icon

> ⚠️ Make sure to back up your project before running the script.

### 📦 Requirements

Add this to your `pubspec.yaml` before running:

```yaml
dev_dependencies:
  flutter_launcher_icons: ^0.14.3
  change_app_package_name: ^1.5.0

flutter_launcher_icons:
  android: true
  ios: true
  image_path: "assets/icons/app_icon.png"
  remove_alpha_ios: true
```

---

### 🔒 License

This project is licensed under the [MIT License](LICENSE).
Feel free to use, modify, and share — just give credit!

---

### ✍️ Author

**Akshay Gupta**
[LinkedIn →](https://www.linkedin.com/in/akshay-gupta-a5868a130/)
[Read full breakdown on Medium →](https://medium.com/@iwritecodeforyou/one-command-to-rebrand-your-flutter-app-project-rename-package-change-icon-update-in-2-1fb169ed5cb1)
