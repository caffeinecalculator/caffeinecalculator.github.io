# Caffeine Calculator

A web app that tracks caffeine intake and shows how it breaks down in your body over time.

## 🚀 Live Demo

Visit: https://caffeinecalculator.github.io

## 📱 Features

### What It Does
- **Drink Database** - Caffeine data from Starbucks, Costa, Dunkin', Monster, Red Bull, and more
- **Metabolism Tracking** - Shows how caffeine leaves your system using the 5-hour half-life rule
- **Timeline Chart** - 36-hour graph showing caffeine levels from all your drinks
- **Sleep Calculator** - Tells you how much caffeine will be in your system at bedtime
- **Custom Drinks** - Add any drink by entering the caffeine amount manually

### Safety Warnings
- **Color-coded Levels**:
  - 🟢 **Green**: Very safe (≤200mg daily, ≤25mg at sleep)
  - 🔵 **Blue**: Safe (≤300mg daily, ≤50mg at sleep)
  - 🟠 **Orange**: Warning (≤400mg daily, ≤100mg at sleep)
  - 🔴 **Red**: Danger (>400mg daily, >100mg at sleep)
- Warnings based on FDA's 400mg daily limit
- Sleep warnings when you have too much caffeine before bed

### Interface
- **Works on Mobile** - Responsive design for phones and tablets
- **Saves Your Data** - Remembers your drinks even after closing the browser
- **Auto-Updates** - Refreshes every minute to show current levels
- **Interactive Chart** - Click legend items to show/hide specific drinks

## 🔬 How It Works

The calculator uses caffeine's 5-hour half-life - meaning half the caffeine is gone every 5 hours:
```
Remaining = Initial × 0.5^(hours_elapsed / 5)
```

### Keep in Mind
- Everyone metabolizes caffeine differently (3-7 hour range)
- Doesn't account for body weight or tolerance
- Assumes instant absorption (actually takes 30-120 minutes)

## 💻 Usage

### Online
Just visit the GitHub Pages URL - nothing to install.

### Run Locally
1. Clone the repo:
   ```bash
   git clone https://github.com/caffeinecalculator/caffeinecalculator.github.io.git
   ```
2. Open `index.html` in your browser

## 🛠️ Tech Stack

- Plain HTML/CSS/JavaScript - no framework needed
- Chart.js for the graphs (loaded from CDN)
- localStorage for saving data
- Works in all modern browsers

## 📄 License

GNU GPL v3 - free software that stays free. See [LICENSE](LICENSE) for details.