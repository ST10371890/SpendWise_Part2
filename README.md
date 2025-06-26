# SpendWise_Part2

SpendWise is a mobile budgeting application developed for Android using Kotlin. It helps users manage expenses, set monthly budgets, view reports, and track financial goals with a simple and intuitive interface.

---

## 🔗 Table of Contents
- [App Features]
- [Installation]
- [Tech Stack]
- [Project Structure]
- [Development Progress (Commits)]
- [License]

---

## 🧪 Tech Stack
- Kotlin
- Android SDK (API 30+)
- Room Database
- MPAndroidChart
- Jetpack Navigation Component
- Material Components
- Firebase Auth (optional)

---

## 📁 Project Structure
```
SpendWise/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/spendwise/...
│   │   │   ├── res/layout/
│   │   │   └── AndroidManifest.xml
├── screenshots/
│   ├── home.png
│   ├── add_expense.png
│   ├── reports.png
│   ├── badges.png
│   └── banner.png
├── README.md
└── LICENSE
```
---
## Features
- Secure login and registration with local encryption
- Add, edit, delete expenses with optional receipt image
- Set total and category-based budgets
- Filter and view expenses by date, category, and amount
- Generate visual spending reports and progress summaries
- Gamified elements with badges and rewards
- Multi-currency support for travel
- Subscription tracking assistant
- Local data storage using SQLite Room DB
- Dark mode and accessibility support

## Installation
1. Clone the repository
```bash
git clone https://github.com/ST10371890/spendwise.git
```
2. Open in Android Studio
3. Build and run on an emulator or Android device

## Development Progress (Commits)
```bash
Initial commit: Added project overview and README
Added initial UI screen mockups (Dashboard, Add Expense, Reports)
Documented app features and technical requirements
Created base MainActivity with navigation placeholders
Added layout files for home screen and bottom navigation
Implemented user login and registration screens
Designed login and registration layouts
Created add expense screen with input form and image upload
Defined Room DB entity for storing expenses
Implemented budget tracking by category
Created model and layout for managing categories
Integrated MPAndroidChart for visual spending reports
Added layout for spending summary charts and filters
Added gamification engine for badge rewards and streaks
Implemented detection of recurring subscriptions
Developed multi-currency conversion for Travel Mode
Fixed UI bugs, improved accessibility support, added dark mode
Final release of SpendWise APK
```

## License
This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.

---

Developed by Mpho Glan Malinga | OPSC6311 Project
