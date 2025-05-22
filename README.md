# NotebookProject 📝

A simple yet powerful **Note-Taking Android App** built with modern Android technologies.  
Easily create, view, and manage your notes with a clean Material Design interface and persistent local storage.

---

## 🚀 Features

- **Create Notes:** Add new notes with a title and content.
- **Edit Notes:** Tap on any note to update its details.
- **View Notes:** All notes are listed in a scrollable, user-friendly list.
- **Delete Notes:** (Swipe-to-delete functionality is scaffolded in code and can be enabled!)
- **Persistent Storage:** Notes are stored locally using SQLite, so your data stays safe on your device.
- **Material Design:** Modern UI with Material Components for a smooth user experience.

---

## 🛠️ Tech Stack

- **Language:** Java 11
- **Minimum SDK:** 24 (Android 7.0)
- **Target SDK:** 34 (Android 14)
- **Build System:** Gradle (Kotlin DSL)
- **UI:** Material Components, ConstraintLayout, RecyclerView
- **Database:** SQLite (via custom `SQLiteHelper`)
- **Testing:** JUnit, Espresso

---

## 📂 Project Structure

```
PracticalProject/
├── app/
│   ├── src/
│   │   └── main/
│   │       ├── java/lk/javainstitute/practicalproject/
│   │       │   ├── MainActivity.java
│   │       │   ├── CreateNoteActivity.java
│   │       │   └── model/SQLiteHelper.java
│   │       ├── res/...
│   │       └── AndroidManifest.xml
├── gradle/
│   └── libs.versions.toml
├── build.gradle.kts
└── settings.gradle.kts
```

---

## 🧑‍💻 How It Works

- **MainActivity:** Displays all notes using a RecyclerView. Tapping the "Create Note" button opens the note editor.
- **CreateNoteActivity:** Lets you add a new note or edit an existing one. Data is saved to SQLite.
- **SQLiteHelper:** Manages the notes database, with a simple schema: `id`, `title`, `content`, `date_created`.

---

## 🏗️ Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/PracticalProject.git
   ```
2. **Open in Android Studio.**
3. **Build & Run** on your emulator or Android device.

---

## ✨ Customization Ideas

- Enable swipe-to-delete for notes (code is scaffolded!).
- Add note search or filtering.
- Implement note categories or tags.
- Sync notes with cloud storage.

---

## 🤝 Contributing

Pull requests and suggestions are welcome!  
Feel free to fork the repo and submit your improvements.

---

**Happy Note-Taking!** 🚀

---

