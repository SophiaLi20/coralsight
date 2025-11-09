# CoralSight - AI Coral Reef Health Assessment

A desktop-based AI/ML solution for automated coral reef health assessment using Convolutional Neural Networks (CNN).

## 🌊 About

CoralSight analyzes coral reef images to classify their health status into four categories:
- **Healthy** - Vibrant, thriving coral
- **Bleached** - Loss of color due to stress
- **Diseased** - Signs of infection
- **Algae-Covered** - Excessive algae growth

## 🚀 Features

- ✅ Fully offline processing (no internet required)
- ✅ Pre-trained CNN model for accurate assessment
- ✅ Data privacy - all processing on local machine
- ✅ Simple and intuitive user interface
- ✅ Instant results with confidence scores

## 📋 Prerequisites

- Node.js (v16 or higher)
- npm or yarn

## 🛠️ Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/coralsight.git
cd coralsight
```

2. Install dependencies:
```bash
npm install
```

3. Run the development server:
```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:5173`

## 🏗️ Build for Production
```bash
npm run build
```

The production files will be in the `dist` folder.

## 🌐 Deployment

### GitHub Pages

1. Update `vite.config.js` with your repository name
2. Build the project: `npm run build`
3. Deploy the `dist` folder to GitHub Pages

### Netlify/Vercel

1. Connect your GitHub repository
2. Build command: `npm run build`
3. Publish directory: `dist`

## 📱 Project Structure
```
coralsight/
├── src/
│   ├── App.jsx          # Main application component
│   ├── main.jsx         # Entry point
│   └── index.css        # Global styles
├── public/              # Static assets
├── index.html           # HTML template
├── package.json         # Dependencies
├── vite.config.js       # Vite configuration
└── tailwind.config.js   # Tailwind CSS configuration
```

## 🔮 Future Enhancements (Final Year)

- [ ] Backend API integration
- [ ] Real CNN model implementation
- [ ] User authentication
- [ ] Analysis history and reports
- [ ] Export functionality
- [ ] Batch processing

## 👥 Team

Final Year Project - [Unnati Bhardwaj, Kshitij Srivastava]

## 📄 License

This project is for educational purposes as part of a final year project.

---

**Note**: This is currently a frontend demonstration. Backend integration with the actual AI model will be implemented in the final phase.