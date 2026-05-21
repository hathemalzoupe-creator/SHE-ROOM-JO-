# 🌍 Multi-Timezone Digital Clock

A modern, responsive web-based clock that displays the current time across multiple timezones simultaneously. Built with vanilla HTML, CSS, and JavaScript—no dependencies required!

## ✨ Features

- 🕐 **Real-time Updates** - Clock updates every second
- 🌍 **24+ Timezones** - New York, London, Tokyo, Sydney, Dubai, Singapore, and many more
- 🔄 **Dynamic Timezone Management** - Add or remove timezones on the fly
- 🎛️ **Time Format Toggle** - Switch between 12-hour and 24-hour formats
- 💾 **Persistent Storage** - Your timezone preferences are saved in browser storage
- 🎨 **Modern Design** - Glassmorphism UI with gradient backgrounds
- 📱 **Fully Responsive** - Works seamlessly on desktop, tablet, and mobile
- 📅 **Date Display** - Shows date for each timezone
- ⚡ **Lightweight** - No external dependencies, pure vanilla JavaScript

## 🚀 Quick Start

### Option 1: Open Locally
1. Download or clone this repository
2. Open `digital-clock.html` in any modern web browser
3. Start exploring timezones!

### Option 2: GitHub Pages
Open the live version at:
```
https://hathemalzoupe-creator.github.io/SHE-ROOM-JO-/digital-clock.html
```

## 📖 How to Use

1. **View Default Timezones** - New York, London, and Tokyo display by default
2. **Add a New Timezone**:
   - Select a timezone from the dropdown menu
   - Click "Add Timezone"
   - The new clock card will appear instantly
3. **Remove a Timezone** - Click the "Remove" button on any clock card
4. **Toggle Time Format** - Use the 24-Hour Format toggle switch
5. **Reset to Defaults** - Click "Reset to Default" to go back to the original three timezones

## 🌐 Available Timezones

The clock supports 24+ major timezones worldwide:

**Americas:**
- New York (EST/EDT)
- Los Angeles (PST/PDT)
- Chicago (CST/CDT)
- Denver (MST/MDT)
- Mexico City
- São Paulo
- Buenos Aires

**Europe & Africa:**
- London (GMT/BST)
- Paris (CET/CEST)
- Berlin (CET/CEST)
- Moscow (MSK)
- Istanbul (EET/EEST)
- Cairo (EET/EEST)

**Asia & Middle East:**
- Dubai (GST)
- Mumbai (IST)
- Bangkok (ICT)
- Singapore (SGT)
- Hong Kong (HKT)
- Shanghai (CST)
- Seoul (KST)
- Tokyo (JST)

**Oceania:**
- Sydney (AEDT/AEST)
- Auckland (NZDT/NZST)
- Honolulu (HST)

## 🎨 Design Features

- **Glassmorphism UI** - Modern frosted glass effect with transparency
- **Gradient Background** - Beautiful blue gradient (#1e3c72 to #2a5298)
- **Smooth Animations** - Hover effects and transitions on all interactive elements
- **Color Scheme**:
  - Timezone names: Light blue (#64b5f6)
  - Time display: White with text shadow
  - AM/PM indicator: Green (#81c784)
  - Background cards: Semi-transparent white

## 💾 Local Storage

Your selected timezones are automatically saved to your browser's local storage. This means:
- Your preferences persist when you close and reopen the page
- Each device stores its own timezone preferences independently
- Clear your browser data to reset preferences

## 📱 Responsive Breakpoints

- **Desktop** - 3+ columns grid layout
- **Tablet** - 2 columns grid layout
- **Mobile** - 1 column full-width layout

## 🛠️ Technical Stack

- **HTML5** - Semantic markup structure
- **CSS3** - Flexbox, Grid, animations, and backdrop filters
- **JavaScript (Vanilla)** - No frameworks or libraries
- **Intl.DateTimeFormat API** - Native timezone handling

## 📋 File Structure

```
SHE-ROOM-JO-/
├── digital-clock.html    # Complete clock application
└── README.md            # Project documentation
```

## 🔧 Code Highlights

### Key JavaScript Functions

```javascript
// Display time in specific timezone
formatTime(date, format24h)

// Get all available timezones
populateTimezoneSelect()

// Add new timezone
addTimezone()

// Remove timezone
removeTimezone(tz)

// Save preferences
localStorage.setItem('selectedTimezones', JSON.stringify(selectedTimezones))
```

### Timezone Data Structure

```javascript
{
  name: 'New York',
  tz: 'America/New_York',
  offset: -5
}
```

## 🌟 Highlights

- **Zero Dependencies** - Pure vanilla code, nothing to install
- **Cross-Browser Compatible** - Works on Chrome, Firefox, Safari, and Edge
- **Fast Loading** - Single HTML file, minimal CSS and JS
- **Accessible** - Clear typography and high contrast colors
- **Environmentally Friendly** - Lightweight footprint

## 📈 Future Enhancements

- [ ] Keyboard shortcuts (arrow keys to navigate, numbers to add timezones)
- [ ] Calculation history and notes
- [ ] World clock map visualization
- [ ] Custom timezone names and colors
- [ ] Dark mode and theme switcher
- [ ] Sound notifications for specific times
- [ ] Alarm functionality
- [ ] Timezone comparison tool
- [ ] Weather integration per timezone
- [ ] Export/import preferences

## 🤝 Contributing

Found a bug or have a feature request? Feel free to:
1. Open an issue on GitHub
2. Submit a pull request with improvements
3. Share feedback and suggestions

## 📄 License

This project is licensed under the **BSD 2-Clause License** - see the LICENSE file for details.

## 👨‍💻 Author

Created by **hathemalzoupe-creator**

## 🙏 Acknowledgments

- Uses JavaScript's native `Intl.DateTimeFormat` API for accurate timezone handling
- Inspired by modern web design principles
- Built with care for global users

---

## ⚡ Quick Tips

1. **Bookmark the GitHub Pages link** - Easy access anytime
2. **Share with team members** - Perfect for distributed teams across timezones
3. **Use in presentations** - Great for discussing global meetings
4. **Mobile-friendly** - Check time zones on the go
5. **No ads or tracking** - Pure, clean experience

---

**Enjoy tracking time across the globe!** 🌍⏰

For more projects, visit: [GitHub Profile](https://github.com/hathemalzoupe-creator)
