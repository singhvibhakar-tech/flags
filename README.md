# 🌍 World Atlas

<p align="center">
  <img src="https://img.shields.io/badge/React-19.2.0-61DAFB?logo=react&logoColor=white" alt="React" />
  <img src="https://img.shields.io/badge/Vite-7.2.2-646CFF?logo=vite&logoColor=white" alt="Vite" />
  <img src="https://img.shields.io/badge/React%20Router-7.9.5-CA4245?logo=react-router&logoColor=white" alt="React Router" />
  <img src="https://img.shields.io/badge/Axios-1.13.2-5A29E4?logo=axios&logoColor=white" alt="Axios" />
  <img src="https://img.shields.io/badge/License-MIT-green.svg" alt="License" />
</p>

<p align="center">
  <b>Explore the world, one country at a time.</b><br>
  A modern, responsive React application to discover countries, their cultures, and detailed information.
</p>

<p align="center">
  <a href="#features">Features</a> •
  <a href="#demo">Demo</a> •
  <a href="#installation">Installation</a> •
  <a href="#screenshots">Screenshots</a> •
  <a href="#technologies">Technologies</a>
</p>

---

## ✨ Features

- 🔍 **Search Countries** - Find any country instantly with real-time search
- 🌎 **Region Filter** - Filter countries by continent (Africa, Americas, Asia, Europe, Oceania)
- ↕️ **Sort Countries** - Sort alphabetically in ascending or descending order
- 🏳️ **Country Flags** - View beautiful SVG flags for all countries
- 📊 **Detailed Information** - Access comprehensive country details including:
  - Population
  - Capital city
  - Region & Sub-region
  - Currency
  - Languages
  - Top Level Domain
- ⚡ **Fast Performance** - Built with Vite for lightning-fast load times
- 📱 **Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices
- 🔄 **Smooth Transitions** - React `useTransition` for non-blocking UI updates

---

## 🚀 Demo

Visit the live application: [World Atlas Demo](https://your-demo-link-here.com)

---

## 🛠️ Installation

### Prerequisites
- Node.js (v18 or higher recommended)
- npm or yarn

### Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/singhvibhakar-tech/flags.git
   cd flags
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:5173`

---

## 📦 Build for Production

```bash
npm run build
```

The production-ready files will be in the `dist` folder.

---

## 🏗️ Project Structure

```
flags/
├── public/
│   └── images/
│       └── world.png           # Hero section image
├── src/
│   ├── api/
│   │   ├── postApi.jsx         # API functions (REST Countries)
│   │   ├── countryData.json    # Local country data
│   │   └── footerApi.json      # Footer data
│   ├── assets/
│   │   └── react.svg
│   ├── components/
│   │   └── Layout/
│   │       ├── AppLayout.jsx   # Main layout wrapper
│   │       ├── CountryCard.jsx # Country card component
│   │       ├── CountryDetails.jsx # Detailed country view
│   │       └── UI/
│   │           ├── Headers.jsx     # Navigation header
│   │           ├── Footers.jsx     # Footer component
│   │           ├── HeroSection.jsx # Landing hero
│   │           ├── Loader.jsx      # Loading spinner
│   │           └── SearchFilter.jsx # Search & filter controls
│   ├── pages/
│   │   ├── Home.jsx            # Home page
│   │   ├── About.jsx           # About page
│   │   ├── Contact.jsx         # Contact page
│   │   ├── Country.jsx         # Countries list page
│   │   └── ErrorPage.jsx       # 404 error page
│   ├── App.jsx                 # Main app component
│   ├── App.css                 # Application styles
│   ├── index.css               # Global styles
│   └── main.jsx                # Entry point
├── index.html
├── package.json
├── vite.config.js
└── README.md
```

---

## 🧰 Technologies

| Technology | Description |
|------------|-------------|
| [React 19](https://react.dev/) | Modern UI library with latest features |
| [Vite](https://vitejs.dev/) | Next-generation frontend build tool |
| [React Router v7](https://reactrouter.com/) | Declarative routing for React |
| [Axios](https://axios-http.com/) | Promise-based HTTP client |
| [React Icons](https://react-icons.github.io/react-icons/) | Popular icon library |
| [REST Countries API](https://restcountries.com/) | Free country data API |

---

## 📸 Screenshots

### 🏠 Home Page
Beautiful landing page with hero section and world map illustration.

### 🌐 Countries Page
Browse all countries with search, filter, and sort functionality.

### 📋 Country Details
In-depth information about each country with flag display.

---

## 🔌 API Reference

This application uses the [REST Countries API](https://restcountries.com/) to fetch country data.

### Endpoints Used

| Endpoint | Description |
|----------|-------------|
| `GET /all?fields=name,population,region,capital,flags` | Get all countries with basic info |
| `GET /name/{name}?fullText=true&fields=...` | Get detailed info for a specific country |

---

## 🎯 Future Enhancements

- [ ] 🌙 Dark mode toggle
- [ ] 🗺️ Interactive world map
- [ ] 📊 Compare countries feature
- [ ] ❤️ Favorite countries list
- [ ] 🔄 Offline support with service workers
- [ ] 🌐 Multi-language support

---

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 👨‍💻 Author

**Vibhakar Singh**

- GitHub: [@singhvibhakar-tech](https://github.com/singhvibhakar-tech)

---

## 🙏 Acknowledgments

- [REST Countries API](https://restcountries.com/) for providing free country data
- [React Icons](https://react-icons.github.io/react-icons/) for the beautiful icon set
- All contributors and supporters of this project

---

<p align="center">
  Made with ❤️ and ☕ by <a href="https://github.com/singhvibhakar-tech">Vibhakar Singh</a>
</p>

<p align="center">
  ⭐ Star this repository if you found it helpful!
</p>
