# 🇵🇸 Mails App – A Smart Way to Manage Citizens' Voice

The **Mails App** is more than just an inbox — it’s a digital bridge between the citizens and their government. Built for the **Prime Minister's Office**, the app helps teams organize, track, and follow up on the thousands of mails received from people every day — with clarity, speed, and purpose.

Our mission? **To give every mail a voice, and every citizen a response.**

---

## ✨ Why This App Matters

In a world of paperwork and overflowing folders, this app transforms the old manual process into a smooth, mobile-friendly experience that’s available anytime, anywhere — making sure **no message gets lost**, and **every concern is heard**.

---

## 🧠 Key Features

### 📊 1. Smart Dashboard at a Glance
- Shows the total number of mails based on:
  - **Category** (e.g., NGOs, Official, Foreign)
  - **Status** (Inbox, Pending, In Progress, Completed)
  - **Tags** (e.g., Urgent, Health, Electricity)
  
![Dashboard](./assets/screenshots/mail_status.png)

---

### 📨 2. Create New Mails in Seconds
- Tap the floating action button
- Fill out sender details, choose a category, add tags
- Set status (e.g., needs review, under processing)

![Inbox Creation](./assets/screenshots/mail_status.png)

---

### 🔎 3. Find Anything – Fast
- Use filters like:
  - Status
  - Tags
  - Dates
  - Keywords
- Simple drawer-based navigation

![Search & Filter](./assets/screenshots/search_filter_drawer.png)

---

### 🧾 4. Organized Senders Page
- View mails grouped by sender
- Search senders by name and view all their previous messages

![Senders](./assets/screenshots/senders_search.png)

---

### 👥 5. User Management with Roles
- Admins can manage:
  - Users
  - Roles
  - Account actions like delete, view profile

![User Management](./assets/screenshots/user_management.png)

---

### 🛠️ 6. Edit Unfinished Mails
- Add missing info or images
- Attach decisions or files
- Update tags or change status

![Edit Mail](./assets/screenshots/tags_edit_mail.png)

---

### 🌐 7. Arabic & English Support
- The app speaks your language!
- Designed for both Arabic (RTL) and English (LTR) users

![Multilingual Auth](./assets/screenshots/auth_screens.png)

---

## 📱 Built With Care

| 💻 Technology | ⚙️ Tools              |
|--------------|------------------------|
| Flutter       | BLoC / Provider        |
| Dart          | Flutter Localizations |
| Firebase / SQLite | Intl for translations |

---

## 🚀 How to Run

```bash
git clone https://github.com/your-username/mails-app.git
cd mails-app
flutter pub get
flutter run
