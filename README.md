# 🏥 Health Monitoring App

A simple and intuitive React application to track daily health metrics and achieve wellness goals.

## 📋 Features

- **Dashboard**: Visual overview of all health metrics with progress tracking
- **Metric Tracking**: Track steps, calories, sleep, water intake, and weight
- **Goal Setting**: Set personalized health goals with recommended targets
- **Progress Visualization**: Progress bars and achievement badges
- **Data Persistence**: Local storage to save your data
- **Weekly Summary**: View your weekly health trends
- **Dark Mode Toggle**: Switch between light and dark themes with persistent preference
- **Reset Data**: Clear all saved data and start fresh with one-click reset functionality
- **Responsive Design**: Works perfectly on desktop and mobile devices

## 🚀 Technologies Used

- **React 18** - Frontend library
- **CSS3** - Styling and responsive design
- **Local Storage** - Data persistence
- **React Hooks** - State management
- **React Context API** - Theme management

## 📦 Installation & Setup

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn package manager

### Steps to Run

1. **Navigate to the project directory:**
   ```bash
   cd Health-Monitoring-App
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Start the development server:**
   ```bash
   npm start
   ```

4. **Open your browser and visit:**
   ```
   http://localhost:3000
   ```

## 🎯 How to Use

### 1. Dashboard
- View all your health metrics at a glance
- See progress bars for each goal
- Check weekly summaries and achievements

### 2. Update Metrics
- Enter your daily health data
- Use quick action buttons for common values
- Track steps, calories, sleep hours, water glasses, and weight

### 3. Set Goals
- Define realistic health targets
- Choose from recommended goal presets
- Adjust goals based on your fitness level

### 4. Reset App Data
- Use the "Reset Data" button in the Goal Setting tab to clear all saved metrics and goals from localStorage. This is useful for starting over or testing the app. Note: this action cannot be undone.

## 📱 Screenshots & Features

### Key Metrics Tracked:
- 🚶‍♂️ **Steps**: Daily step count with customizable goals
- 🔥 **Calories**: Calorie intake tracking
- 😴 **Sleep**: Sleep hours with quality tracking
- 💧 **Water**: Hydration monitoring (glasses per day)
- ⚖️ **Weight**: Weight tracking and goal setting

### Smart Features:
- ✅ Achievement badges when goals are met
- 📊 Weekly progress summaries
- 💾 Automatic data saving
- 📱 Mobile-responsive design
- 🎯 SMART goal recommendations

## 🏗️ Project Structure

```
Health-Monitoring-App/
├── public/
│   ├── index.html
│   └── manifest.json
├── src/
│   ├── components/
│   │   ├── Dashboard.js
│   │   ├── MetricInput.js
│   │   └── GoalSetting.js
│   ├── App.js
│   ├── App.css
│   ├── index.js
│   └── index.css
├── package.json
└── README.md
```

## 🔧 Available Scripts

- `npm start` - Run the app in development mode
- `npm test` - Launch the test runner
- `npm run build` - Build the app for production
- `npm run eject` - Eject from Create React App (one-way operation)

## 🎨 Customization

### Adding New Metrics
1. Update the metrics array in `App.js`
2. Add corresponding UI in `Dashboard.js`
3. Include input fields in `MetricInput.js`
4. Add goal setting in `GoalSetting.js`

### Styling
- Modify `index.css` for global styles
- Update `App.css` for component-specific styles
- All styles are responsive and mobile-friendly

## 🤝 Contributing

This project is part of the React Projects for Beginners repository. To contribute:

1. Fork the repository
2. Create a new branch (`git checkout -b feature-name`)
3. Make your changes
4. Commit your changes (`git commit -m 'Add some feature'`)
5. Push to the branch (`git push origin feature-name`)
6. Open a Pull Request

## 📊 Future Enhancements

- [ ] Charts and graphs for trend visualization
- [ ] Export data functionality
- [ ] Social sharing features
- [ ] Integration with fitness trackers
- [ ] Nutrition database integration
- [ ] Reminder notifications
- [ ] Dark mode toggle
- [ ] Multi-user support


## 🙏 Acknowledgments

- Created as part of Hacktoberfest 2025
- Thanks to the React community for excellent documentation
- Icons and emojis for enhanced user experience

---

**Happy tracking! Stay healthy! 🌟**

For questions or suggestions, please open an issue in the main repository.
