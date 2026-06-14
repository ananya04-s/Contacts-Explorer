# 📱 Contact Explorer

A modern Android application built using **Kotlin** that allows users to view and search contacts stored on their device. The app demonstrates how to request runtime permissions, retrieve contacts using Android's `ContentResolver`, and display them in a clean, user-friendly interface.

---

## ✨ Features

- 📞 View all contacts stored on the device
- 🔍 Search contacts by name or phone number
- 🛡️ Runtime permission handling for `READ_CONTACTS`
- 📋 Beautiful RecyclerView/ListView with Material Design
- 👤 Displays contact name and phone number
- 🔄 Pull-to-refresh functionality
- 📊 Shows total number of contacts
- 🎨 Modern and responsive UI
- 📱 Supports both real device contacts and optional sample dataset
- ⚡ Fast loading and smooth scrolling

---

## 🛠️ Tech Stack

- **Language:** Kotlin
- **IDE:** Android Studio
- **UI:** XML + Material Design 3
- **Architecture:** MVVM-friendly structure
- **API Used:** Android ContactsContract
- **Permissions:** READ_CONTACTS
- **Components:** RecyclerView, SearchView, ContentResolver, ViewBinding

---

## 📂 Project Structure

```
ContactExplorer/
│
├── app/
├── java/
│   ├── MainActivity.kt
│   ├── ContactAdapter.kt
│   ├── ContactModel.kt
│   ├── ContactRepository.kt
│   └── PermissionUtils.kt
│
├── res/
│   ├── layout/
│   ├── drawable/
│   ├── values/
│   └── mipmap/
│
├── AndroidManifest.xml
└── README.md
```

---

## 🚀 How It Works

1. Launch the application.
2. Grant contact permission when prompted.
3. The app retrieves contacts using Android's `ContentResolver`.
4. Contacts are displayed in a searchable list.
5. Use the search bar to quickly find a contact by name or phone number.

---

## 🔐 Permissions Used

```xml
<uses-permission android:name="android.permission.READ_CONTACTS"/>
```

The app requests this permission at runtime to securely access the device's contacts.

---

## 🧪 Testing

- ✅ Works on physical Android devices with stored contacts.
- ✅ Can optionally display a sample dataset for emulator testing.
- ✅ Handles denied permissions gracefully.
- ✅ Prevents duplicate contact entries.
- ✅ Displays loading and empty states appropriately.

---

## 📸 Key Screens

- Splash Screen
- Permission Request Screen
- Home Dashboard
- Contact List
- Search Results
- Empty State (No Contacts)
- Error & Retry State

---

## 🌟 Future Enhancements

- ⭐ Favorite contacts
- 📞 One-tap calling
- 💬 SMS shortcut
- 📧 Email integration
- 👥 Contact grouping
- 🌙 Dark mode
- ☁️ Cloud backup and sync
- 📤 Export contacts to CSV or PDF
- 🔤 Alphabetical quick-scroll index

---

## 🎯 Learning Outcomes

This project demonstrates:
- Runtime permission handling in Android
- Working with `ContentResolver`
- Fetching data from `ContactsContract`
- RecyclerView implementation
- Search and filtering
- Material Design principles
- Android lifecycle and best practices

---

## 👨‍💻 Author

Developed as an Android learning project and portfolio application to explore contact management, permissions, and modern UI development in Kotlin.

---

## 📜 License

This project is intended for educational and demonstration purposes.
