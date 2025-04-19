# 💧 H2OHero-App

**Stay hydrated, stay healthy!**  
H2OHero is a personal hydration tracker that helps you develop healthier drinking habits. Track your water intake, receive intelligent reminders, and analyze your progress — all in one app, with iPhone, iPad, and Apple Watch support.

---

## 🚀 Features

- 🧠 Personalized hydration goals based on age, gender, weight, height, and activity level
- 📅 Daily log and visual statistics (weekly/monthly trends)
- 🔔 Smart reminders to prevent dehydration and overhydration
- ☁️ Cloud sync via iCloud (multi-device support)
- ⌚️ Apple Watch companion app with quick log and HealthKit integration
- 🌡️ Water temperature awareness and health warnings
- 📈 AI-based analysis and personalized suggestions
- 🌍 Bilingual interface (English / 中文)

---

## 🧱 Tech Stack

- `Swift` + `SwiftUI`
- `CloudKit` / `CoreData`
- `HealthKit` / `WatchConnectivity`
- `Swift Charts` for visualization
- `CoreML` (planned for AI recommendation model)

---

## 📦 Installation

```bash
git clone https://github.com/Yucheng0208/H2OHero-App.git
cd H2OHero-App
open H2OHero-App.xcodeproj
```
- Requires: Xcode 15+, iOS 17+, WatchOS 10+

 ## 📂 Project Structure
```bash
H2OHero-App/
├── ContentView.swift           # Main UI & hydration dashboard
├── HydrationManager.swift     # Core hydration logic
├── UserProfile.swift          # User profile model
├── HydrationEntry.swift       # Drinking logs model
├── WatchKit Extension/        # Apple Watch companion app (planned)
└── Resources/
    └── Localizable.strings    # Language support (EN / ZH)
```

## LICENSE
This project is licensed under the EPL-2.0 License - see the [LICENSE](LICENSE) file for details.
