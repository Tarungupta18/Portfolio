# Modern Portfolio Website 🎨

<div align="center">
    <img src="https://img.shields.io/badge/React-18.2.0-61DAFB?style=for-the-badge&logo=react&logoColor=white" alt="React"/>
    <img src="https://img.shields.io/badge/Three.js-black?style=for-the-badge&logo=three.js&logoColor=white" alt="Three.js"/>
    <img src="https://img.shields.io/badge/Material%20UI-007FFF?style=for-the-badge&logo=mui&logoColor=white" alt="Material UI"/>
    <img src="https://img.shields.io/badge/Framer-0055FF?style=for-the-badge&logo=framer&logoColor=white" alt="Framer"/>
</div>

## ✨ Features

- 🎨 3D Graphics with Three.js and React Three Fiber
- 🎭 Smooth animations using Framer Motion
- 💅 Styled with Material UI and Styled Components
- 📧 Email integration with EmailJS
- ⌨️ Interactive typing animations
- 📱 Fully responsive design
- 🌐 GitHub Pages deployment ready
- 📜 Vertical timeline component for experience/projects
- 🔄 Custom scroll animations

## 🛠️ Technology Stack

- **Frontend Framework**: React 18
- **3D Graphics**: Three.js, @react-three/fiber, @react-three/drei
- **Styling**: Material UI, Styled Components
- **Animations**: Framer Motion, Typewriter Effect
- **Icons**: Material Icons, React Icons
- **Routing**: React Router DOM
- **Email Service**: EmailJS
- **Deployment**: GitHub Pages

## 📥 Installation

1. **Clone the repository**
```bash
git clone https://github.com/Tarungupta18/portfolio-website.git
cd portfolio-website
```

2. **Install dependencies**
```bash
npm install
```

3. **Start development server**
```bash
npm start
```

## 🚀 Deployment

### GitHub Pages Deployment

1. **Update homepage**
In `package.json`, ensure the homepage is set to your GitHub Pages URL:
```json
{
  "homepage": "https://Tarungupta18.github.io"
}
```

2. **Deploy**
```bash
npm run deploy
```

## 📁 Project Structure

```
portfolio-website/
├── public/
├── src/
│   ├── components/
│   ├── assets/
│   ├── styles/
│   ├── utils/
│   ├── App.js
│   └── index.js
├── package.json
└── README.md
```

## 🔧 Configuration

### EmailJS Setup

1. Create an account at [EmailJS](https://www.emailjs.com/)
2. Create a `.env` file in the root directory:
```env
REACT_APP_EMAILJS_SERVICE_ID=your_service_id
REACT_APP_EMAILJS_TEMPLATE_ID=your_template_id
REACT_APP_EMAILJS_USER_ID=your_user_id
```

## 🎨 Customization

### Themes
- Material UI themes can be customized in the theme configuration file
- Styled Components global styles can be modified for consistent styling

### 3D Models
- Place your 3D models in the `public/models` directory
- Update the model paths in your Three.js components

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 Scripts

- `npm start`: Start development server
- `npm build`: Build for production
- `npm test`: Run tests
- `npm run deploy`: Deploy to GitHub Pages
- `npm run eject`: Eject from Create React App

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Contact

Tarun Gupta - tkg21430@gmail.com

Project Link: [https://github.com/Tarungupta18/portfolio-website](https://github.com/Tarungupta18/portfolio-website)

*Made with ❤️ and React*
