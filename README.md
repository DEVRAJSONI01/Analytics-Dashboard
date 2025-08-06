# Analytics Dashboard

A modern, interactive analytics dashboard built with React and Vite, featuring real-time data visualization and smooth animations.

## 🚀 Features

### 📊 Interactive Charts
- **Revenue Trend**: Line chart showing revenue progression over time
- **User Activity**: Area chart displaying user engagement metrics
- **Traffic Sources**: Pie chart breaking down traffic by source
- **Conversions**: Bar chart showing conversion rates across different periods

### 🎮 Dynamic Controls
- **Single Point Mode**: Navigate through individual time periods with a single slider point
- **Range Mode**: Select date ranges with dual handles and custom checkmark icons
- **Play/Pause Animation**: Smooth continuous animation cycling through all time periods
- **Manual Navigation**: Previous/Next buttons for precise control

### 📈 KPI Cards
- Total Revenue with percentage change indicators
- Active Users count with trend analysis
- Session metrics with period-over-period comparison
- Conversion Rate tracking
- Page Views monitoring

### ⚡ Performance Features
- Smooth 60fps animations using `requestAnimationFrame`
- Real-time data updates
- Responsive design for all devices
- Interactive hover effects and tooltips

## 🛠️ Tech Stack

- **Frontend**: React 18.2.0
- **Build Tool**: Vite 4.4.5
- **Charts**: Recharts 2.8.0
- **Icons**: Lucide React 0.263.1
- **Styling**: CSS3 with custom animations

## 📦 Installation

1. Clone the repository:
```bash
git clone https://github.com/DEVRAJSONI01/Analytics-Dashboard.git
cd Analytics-Dashboard
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:5173`

## 🏗️ Build for Production

```bash
npm run build
```

The built files will be available in the `dist` folder.

## 📱 Usage

### Time Period Navigation
- **Toggle Switch**: Switch between "Single Point" and "Range" selection modes
- **Play Button**: Start/stop automatic animation through time periods
- **Slider Interaction**: Click or drag to manually select time periods
- **Arrow Controls**: Use previous/next buttons for step-by-step navigation

### Chart Interactions
- **Hover Effects**: Hover over chart elements to see detailed tooltips
- **Real-time Updates**: All charts update automatically as you change time periods
- **Smooth Transitions**: All animations use CSS cubic-bezier easing for professional feel

## 🎨 Design Features

- **Dark Theme**: Modern dark UI with purple accent colors
- **Gradient Effects**: Beautiful gradients throughout the interface
- **Smooth Animations**: 1200ms animation duration with easing
- **Responsive Layout**: Works perfectly on desktop, tablet, and mobile

## 📊 Sample Data

The dashboard includes 5 time periods with realistic sample data:
- Jan 1-7: Initial metrics
- Jan 8-14: Growth period  
- Jan 15-21: Peak performance
- Jan 22-28: Stabilization
- Jan 29-Feb 4: Optimization phase

## 🔧 Customization

### Adding New Time Periods
Edit the `timePoints` array in `TimePeriodSelector.jsx`:

```javascript
const timePoints = [
  { start: 'Jan 1', end: 'Jan 7', current: 'Jan 1 - Jan 7', weeks: 1 },
  // Add your custom time periods here
];
```

### Modifying Chart Data
Update the data arrays in `Charts.jsx` and `KPICards.jsx` to reflect your metrics.

### Styling Changes
All styles are in component-specific CSS files for easy customization.

## 🚀 Deployment

This project is ready for deployment on:
- **Netlify**: Drag and drop the `dist` folder
- **Vercel**: Connect your GitHub repository
- **GitHub Pages**: Enable Pages in repository settings

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Author

**Devraj Soni**
- GitHub: [@DEVRAJSONI01](https://github.com/DEVRAJSONI01)

---

⭐ Star this repository if you found it helpful!
