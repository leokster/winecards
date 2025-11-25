# WineCards

A native iOS flashcard app for WSET Level 2 wine certification preparation.

![iOS](https://img.shields.io/badge/iOS-15.0+-blue.svg)
![Swift](https://img.shields.io/badge/Swift-5.0-orange.svg)
![License](https://img.shields.io/badge/License-Proprietary-red.svg)

## Overview

WineCards is a simple, elegant flashcard application designed to help wine students prepare for the WSET Level 2 certification exam. The app features a clean interface, smooth animations, and focuses on effective study through random question presentation and personalized question marking.

## Features

- 🎴 **Flashcard Study Mode** - Random question presentation
- ⭐ **Star Questions** - Mark important questions for later review
- 📱 **Native iOS** - Built with SwiftUI for optimal performance
- 🎨 **Beautiful UI** - Purple gradient design with smooth animations
- 👆 **Swipe Gestures** - Natural swipe-to-advance functionality
- 🖼️ **Image Support** - Wine label images in questions
- 📴 **Offline Mode** - Works without internet (images may need connection)
- 🔒 **Privacy First** - No data collection, all storage local
- 🌐 **German Language** - UI in German (Deutsch)

## Screenshots

[Add screenshots here]

## Technical Details

### Architecture
- **Platform:** iOS 15.0+
- **Language:** Swift 5.0
- **Framework:** SwiftUI
- **Pattern:** MVVM (Model-View-ViewModel)
- **Storage:** UserDefaults (local only)
- **Bundle ID:** com.timrohner.winecards

### Key Components
- `FlashcardView.swift` - Main UI and swipe gestures
- `FlashcardViewModel.swift` - Business logic and state management
- `Models.swift` - Data structures
- `HTMLHelper.swift` - HTML parsing for questions
- `questions.json` - Question database

### Dependencies
- None - Pure SwiftUI application

## Privacy & Data

**Zero Data Collection:**
- No analytics
- No tracking
- No user accounts
- No cloud storage
- All data stored locally on device

See [Privacy Policy](PRIVACY_POLICY.md) for full details.

## Build & Installation

### Requirements
- Xcode 13.0 or later
- macOS 12.0 or later
- iOS 15.0+ device or simulator
- Apple Developer account (for device deployment)

### Building from Source

1. **Clone the repository**
   ```bash
   git clone [repository-url]
   cd winecards
   ```

2. **Open in Xcode**
   ```bash
   cd FlashcardsApp
   open FlashcardsApp.xcodeproj
   ```

3. **Configure Signing**
   - Select the project in Xcode
   - Go to "Signing & Capabilities"
   - Select your development team
   - Ensure bundle ID is unique if changed

4. **Build and Run**
   - Select target device or simulator
   - Press ⌘R or click Run button

### App Store Deployment

See [App Store Submission Guide](APP_STORE.md) for detailed instructions.

## Usage

### Study Mode
1. Launch the app
2. View random questions
3. Tap an answer to select
4. Correct/incorrect feedback shown
5. Swipe left or tap "Nächste Frage" for next question

### Starring Questions
1. While viewing a question, tap the ⭐ button
2. Question is saved to your favorites
3. Access starred questions via "Markiert" button

### Starred Questions List
1. Tap "Markiert" at the top
2. View all your starred questions
3. Tap any question to study it
4. Tap star to unstar

## Project Structure

```
FlashcardsApp/
├── FlashcardsApp/
│   ├── FlashcardsApp.swift           # App entry point
│   ├── FlashcardView.swift           # Main UI
│   ├── FlashcardViewModel.swift      # View model
│   ├── Models.swift                  # Data models
│   ├── HTMLHelper.swift              # HTML utilities
│   ├── questions.json                # Question database
│   └── Assets.xcassets/              # App icon & assets
├── FlashcardsApp.xcodeproj/          # Xcode project
├── README.md                         # This file
├── PRIVACY_POLICY.md                 # Privacy policy
├── TERMS_OF_SERVICE.md               # Terms of service
├── DATA_PROTECTION.md                # GDPR compliance
├── SUPPORT.md                        # User support
└── APP_STORE.md                      # App Store info
```

## Contributing

This is a proprietary application. Contributions are not currently accepted.

## Known Issues

- Images require internet connection to load
- No iPad-optimized layout (works but not optimized)
- German language only

## Future Enhancements

Potential features for future versions:
- [ ] Search functionality
- [ ] Statistics and progress tracking
- [ ] Multiple language support
- [ ] iPad-optimized UI
- [ ] Export starred questions
- [ ] Custom study sessions
- [ ] Spaced repetition algorithm
- [ ] Dark mode support

## Version History

### Version 1.0.0 (2024-11-24)
- Initial release
- Flashcard study mode
- Star/favorite questions
- Swipe gestures
- Image support
- Offline functionality

## Support

For support, bug reports, or feature requests:

**Email:** [Your Support Email]
**Documentation:** [SUPPORT.md](SUPPORT.md)

## Legal

### Copyright
© 2024 Tim Rohner. All rights reserved.

### License
Proprietary - All rights reserved. This software is provided for personal use only.

### Terms & Privacy
- [Terms of Service](TERMS_OF_SERVICE.md)
- [Privacy Policy](PRIVACY_POLICY.md)
- [Data Protection](DATA_PROTECTION.md)

### Disclaimer
This app is not affiliated with, endorsed by, or officially connected to the Wine & Spirit Education Trust (WSET). It is an independent study tool.

## Acknowledgments

- Question content: Académie du Vin
- Wine label images: Various sources
- Icon: [If applicable]

## Contact

**Developer:** Tim Rohner
**Email:** [Your Email]
**Bundle ID:** com.timrohner.winecards

---

Built with ❤️ and SwiftUI
