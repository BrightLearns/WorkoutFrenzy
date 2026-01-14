# 💪 WorkoutFrenzy - Personal Workout Tracker

![WorkoutFrenzy](https://img.shields.io/badge/WorkoutFrenzy-Live-purple?style=for-the-badge)
![Version](https://img.shields.io/badge/version-1.0.0-blue?style=for-the-badge)
![License](https://img.shields.io/badge/license-All%20Rights%20Reserved-red?style=for-the-badge)

A powerful, personalized workout tracking application that adapts to your fitness goals, available equipment, and training schedule.

## ✨ Features

- 🎯 **3 Fitness Goals**: Build Muscle, Lose Weight, Keep Fit
- 🏠 **Home & Gym Modes**: Workouts adapt to your environment
- 🔧 **Equipment-Based**: 40+ gym equipment options, customizable home setups
- 📊 **Dynamic Tracking**: Set inputs automatically match your workout (3 sets = 3 inputs)
- 📈 **Progress History**: Detailed workout logs with reps & weight per set
- 🍲 **Nigerian Nutrition**: Food-focused meal guides
- 🔥 **Streak Counter**: Track consecutive workout days
- 💪 **Daily Motivation**: Snarky quotes to keep you fired up
- 🎨 **Beautiful UI**: Dark theme with purple gradients
- 📱 **PWA Ready**: Install as a mobile app
- 💾 **LocalStorage**: All data saved locally in browser

## 🚀 Quick Start

### Option 1: Deploy to Vercel (Recommended)

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/YOUR_USERNAME/workoutfrenzy)

1. Click the button above
2. Sign in to Vercel with GitHub
3. Create a new repository (or select existing)
4. Click "Deploy"
5. Done! Your app is live! 🎉

### Option 2: GitHub Pages

1. Fork this repository
2. Go to Settings → Pages
3. Source: Deploy from main branch
4. Your site will be live at `https://yourusername.github.io/workoutfrenzy`

### Option 3: Local Development

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/workoutfrenzy.git

# Navigate to directory
cd workoutfrenzy

# Open in browser (no build needed!)
open index.html
# Or use a simple HTTP server:
python -m http.server 8000
```

## 📂 Project Structure

```
workoutfrenzy/
├── index.html          # Main application (single file app!)
├── manifest.json       # PWA manifest
├── robots.txt          # SEO configuration
├── vercel.json         # Vercel deployment config
└── README.md           # This file
```

## 🎯 How It Works

### 1. **Onboarding**
First-time users go through a quick setup:
- Enter your name
- Choose fitness goal
- Select training environment
- Pick available equipment
- Set training schedule

### 2. **Daily Workouts**
- View your personalized workout for today
- Track sets, reps, and weight
- See dynamic motivational quotes
- Monitor your completion progress
- Finish workout to log it

### 3. **Goal & Settings**
- Adjust your fitness goal anytime
- Switch between home/gym
- Modify equipment selection
- Change training days (e.g., Mon/Wed/Fri)
- Save changes

### 4. **Nutrition Guide**
- Goal-specific meal plans
- Nigerian food focus
- Breakfast, lunch, dinner suggestions
- Training day & rest day layouts

### 5. **History**
- View all completed workouts
- Click cards to see detailed breakdown
- Track progressive overload
- Monitor consistency

## 🛠️ Technical Stack

- **Frontend**: Pure HTML5, CSS3, JavaScript (ES5+)
- **Storage**: Browser LocalStorage API
- **Icons**: Inline SVG (no external dependencies)
- **Design**: CSS Grid, Flexbox, CSS Variables
- **PWA**: Service Workers ready
- **Build**: None! Pure static site

## 🌐 Browser Support

- ✅ Chrome/Edge (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 📱 Mobile App Experience

### iOS (Safari)
1. Visit the site
2. Tap Share button
3. Select "Add to Home Screen"
4. Enjoy native-like app!

### Android (Chrome)
1. Visit the site
2. Tap menu (⋮)
3. Select "Add to Home screen"
4. Launch from home screen!

## 🎨 Customization

### Changing Colors
Edit CSS variables in `index.html`:
```css
:root {
  --accent-primary: #a855f7;    /* Purple */
  --accent-secondary: #ec4899;   /* Pink */
  --success: #10b981;            /* Green */
}
```

### Adding Workout Plans
Edit the `WORKOUT_PLANS` object in `index.html` to add more workout templates.

### Adding Equipment
Edit `EQUIPMENT_EXERCISES` object to add more home/gym equipment options.

## 📊 Data & Privacy

- ✅ **All data stored locally** in your browser
- ✅ **No backend server** required
- ✅ **No data collection** or tracking
- ✅ **Complete privacy** - your data never leaves your device
- ⚠️ **Important**: Clear browser data = lose your history

## 🔧 Development

No build process required! Just edit `index.html` and refresh.

```bash
# Run local server (optional)
python -m http.server 8000

# Or use Node.js
npx serve .

# Or use PHP
php -S localhost:8000
```

## 📝 Version History

### v1.0.0 (Current)
- ✅ Core workout tracking
- ✅ Equipment-based plans
- ✅ Dynamic set inputs
- ✅ Detailed history
- ✅ PWA support
- ✅ Help & FAQ system

## 🤝 Contributing

This is a personal project. Feel free to fork and customize for your own use!

## 📄 License

All rights reserved. This code is provided for personal use only.

## 👨‍💻 Author

**Bright**

---

## 🙏 Acknowledgments

- Inspired by fitness tracking needs
- Built with pure vanilla JavaScript
- No frameworks, no dependencies, just raw code

## 📞 Support

For issues or questions:
1. Check the in-app Help & FAQ (? button)
2. Review this README
3. Open an issue on GitHub

---

**Made with 💪 and ☕**

*WorkoutFrenzy - Track. Progress. Dominate.*
