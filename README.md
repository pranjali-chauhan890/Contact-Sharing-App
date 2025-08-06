# 📇 Contact Sharing App

An Android application that allows users to share contact details quickly and easily. This app demonstrates core Android components like Intents, Contacts API, and data sharing between apps.

⭐ If you like this project, please give it a *star* to show your support!

---

## ✨ Features

- 📤 Share contact details via SMS, email, or other apps  
- 📱 Select contact from phonebook  
- ✍ Manually enter and share contact information  
- 🔒 Handles permission requests for accessing contacts  
- 💡 Clean and user-friendly interface

---

## 🛠 Built With

- *Java*
- *XML*
- *Android Studio*
- *Intent* and *ShareCompat* for sharing contact info  
- *ContactsContract* for accessing phonebook  
- *Runtime Permissions* for contact access  
- *Material Design UI components*

---

## 🔧 Logic Used

- Uses Intent.ACTION_PICK to choose a contact from the device  
- Retrieves data using ContactsContract.CommonDataKinds  
- Shares contact via Intent.ACTION_SEND  
- Permissions handled using ActivityCompat.requestPermissions and onRequestPermissionsResult
