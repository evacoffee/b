# Beautify - AI-Powered Skincare Platform

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/evacoffee/beautify/blob/main/LICENSE)
[![GitHub issues](https://img.shields.io/github/issues/evacoffee/beautify)](https://github.com/evacoffee/beautify/issues)
[![GitHub stars](https://img.shields.io/github/stars/evacoffee/beautify)](https://github.com/evacoffee/beautify/stargazers)

## 🌟 Features

- 🧠 AI-Powered Skin Analysis
  - Face detection and analysis
  - Skin type classification
  - Skin concern detection
  - Product compatibility analysis

- 🔄 Personalized Skincare Routines
  - Custom routine generation
  - Product recommendations
  - Progress tracking
  - Effectiveness monitoring

- 🎥 Interactive Makeup Tutorials
  - Video-based learning
  - Step-by-step guides
  - AR makeup try-on
  - Tutorial progress tracking

- 🌐 Community Features
  - Product reviews and ratings
  - Discussion forums
  - User-generated content
  - Community recommendations

## 🚀 Technologies Used

- Frontend:
  - React.js
  - Redux for state management
  - Material-UI
  - Three.js for AR features

- Backend:
  - Node.js with Express
  - MongoDB
  - Redis for caching
  - Socket.io for real-time features

- AI/ML:
  - TensorFlow.js
  - OpenCV
  - Dlib
  - Scikit-learn

## 🛠️ Project Structure

```
beautify/
├── client/                  # Frontend React application
│   ├── src/
│   │   ├── components/     # Reusable React components
│   │   ├── pages/         # Page components
│   │   ├── hooks/         # Custom React hooks
│   │   ├── utils/         # Utility functions
│   │   └── store/         # Redux store
│   └── public/
├── server/                 # Backend Node.js application
│   ├── src/
│   │   ├── routes/       # API routes
│   │   ├── controllers/  # Route controllers
│   │   ├── models/       # MongoDB models
│   │   └── services/     # Business logic
├── ai/                     # AI/ML models and services
│   ├── models/           # ML models
│   └── services/         # AI services
└── docs/                  # Documentation
```

## 📝 Installation

1. Clone the repository:
```bash
git clone https://github.com/evacoffee/beautify.git
cd beautify
```

2. Install dependencies:
```bash
# Install frontend dependencies
cd client
npm install

# Install backend dependencies
cd ../server
npm install
```

3. Start the development servers:
```bash
# Start frontend
cd client
npm start

# Start backend
cd ../server
npm run dev
```

## 🔧 Configuration

Create a `.env` file in both `client` and `server` directories:

```.env
# Frontend
REACT_APP_API_URL=http://localhost:5000
REACT_APP_MAP_API_KEY=your_map_api_key

# Backend
PORT=5000
MONGODB_URI=mongodb://localhost:27017/beautify
JWT_SECRET=your_jwt_secret
```

## 📈 Project Statistics

- Total Lines of Code: ~46,000
- Number of Components: 120+
- API Endpoints: 50+
- ML Models: 5
- Database Collections: 15
- Test Cases: 300+

## 🎯 Project Goals

1. Provide personalized skincare solutions using AI
2. Create an engaging community platform
3. Offer interactive learning experiences
4. Implement real-time features for better user engagement

## 📋 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
