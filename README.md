# 🎬 Netflix Clone

A pixel-perfect Netflix clone featuring authentication, movie browsing, and watchlist functionality. Built with modern web technologies to replicate the Netflix experience.

**Live Demo:** [Add your deployment link]

---

## 🧠 Author

| Member | Position | Responsibilities |
|--------|----------|------------------|
| Sergio Sediq | Full Stack Developer | Frontend Architecture (React, TypeScript), Firebase Authentication, TMDB API Integration, UI/UX Design (Styled Components), Video Player Controls |

---

## 🛠️ Technologies

- **React.js** - Component-based UI library
- **TypeScript** - Type-safe development
- **Firebase** - Authentication and backend services
- **Styled Components** - CSS-in-JS styling solution
- **TMDB API** - Movie data and information
- **Vite** - Fast development build tool

---

## 🎉 Features

- **User Authentication** - Sign up, sign in, and secure user sessions with Firebase
- **Browse Movies & TV Shows** - Explore content across multiple categories
- **Trailer Playback** - Watch trailers with mute/unmute controls
- **Watchlist Management** - Save movies and shows to your personal list
- **Detailed Movie Info** - View ratings, descriptions, and cast information
- **Responsive Design** - Seamless experience across all devices
- **Netflix-like UI** - Faithful recreation of Netflix's interface

---

## 🚦 Getting Started

### Prerequisites

- Node.js 16+
- npm or yarn
- Firebase account
- TMDB API key

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/SergioSediq/netflix-clone.git
cd netflix-clone
```

2. **Install dependencies**
```bash
npm install
# or
yarn install
```

3. **Set up environment variables**

Create a `.env` file in the root directory:
```env
VITE_FIREBASE_API_KEY=your_firebase_api_key
VITE_FIREBASE_AUTH_DOMAIN=your_auth_domain
VITE_FIREBASE_PROJECT_ID=your_project_id
VITE_FIREBASE_STORAGE_BUCKET=your_storage_bucket
VITE_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
VITE_FIREBASE_APP_ID=your_app_id
VITE_TMDB_API_KEY=your_tmdb_api_key
```

4. **Run development server**
```bash
npm run dev
# or
yarn dev
```

5. **Open in browser**

Navigate to `http://localhost:5173`

---

## 📂 Project Structure
```
NETFLIX-CLONE/
├── public/              # Static assets
│   ├── avatar.png      # User profile avatars
│   ├── banner.jpg      # Hero banners
│   ├── trailer.mp4     # Sample trailer video
│   └── *.png, *.ico    # Icons and images
│
├── src/
│   ├── Components/     # Reusable React components
│   ├── Context/        # React context providers
│   ├── library/        # Utility functions and helpers
│   ├── pages/          # Page components (Home, Browse, etc.)
│   ├── styles/         # Global styles and themes
│   ├── utilities/      # Helper utilities
│   ├── App.tsx         # Main app component
│   └── main.tsx        # App entry point
│
├── index.html          # HTML entry
├── vite.config.ts      # Vite configuration
├── tsconfig.json       # TypeScript config
└── package.json        # Dependencies
```

---

## 🔑 API Setup

### Firebase Configuration

1. Create a Firebase project at [firebase.google.com](https://firebase.google.com)
2. Enable Authentication (Email/Password)
3. Create a Firestore database
4. Copy your config to `.env`

### TMDB API Key

1. Sign up at [themoviedb.org](https://www.themoviedb.org/)
2. Go to Settings → API
3. Request an API key
4. Add to `.env` file

---

## 🎥 Demo

<details>
<summary><h3>📹 Video Demo</h3></summary>

https://user-images.githubusercontent.com/71933266/206354982-e53f92de-6462-44f1-ab51-4e51c9816581.mp4

</details>

<details>
<summary><h3>📸 Screenshots</h3></summary>

### Home Page
![netflix1](https://user-images.githubusercontent.com/71933266/206354412-b53ec961-117f-4c4d-9509-a63d9d597067.png)

### Browse Content
![netflix2](https://user-images.githubusercontent.com/71933266/206354420-ad7c4b82-4815-423e-b8d6-5fa7791acd80.png)

### Movie Details
![netflix3](https://user-images.githubusercontent.com/71933266/206354434-51944382-4d2d-4405-817c-314297da7a1b.png)

### My List
![netflix4](https://user-images.githubusercontent.com/71933266/206354455-3c628617-0dab-41f5-8383-89ad3f5c9801.png)

</details>

---

## 💡 Key Features Breakdown

### Authentication System
- Email/password sign up and login
- Secure session management with Firebase
- Protected routes for authenticated users

### Movie Browsing
- Multiple content categories (Trending, Popular, Top Rated)
- Genre-based filtering
- Search functionality
- Dynamic content loading

### Video Player
- Embedded trailer playback
- Mute/unmute controls
- Autoplay on hover (Netflix-style)

### Watchlist
- Add/remove movies and shows
- Persistent storage with Firebase
- Real-time updates

---

## 🚀 Deployment

### Build for Production
```bash
npm run build
# or
yarn build
```

### Deploy to Vercel
```bash
npm install -g vercel
vercel
```

---

## 💡 Future Enhancements

- [ ] **Multiple Profiles** - User profiles like real Netflix
- [ ] **Continue Watching** - Resume playback feature
- [ ] **Recommendations** - Personalized suggestions
- [ ] **Download Feature** - Offline viewing
- [ ] **Subtitle Support** - Multiple languages
- [ ] **Kids Mode** - Child-friendly content
- [ ] **Watch History** - Viewing history tracking
- [ ] **Rating System** - User ratings and reviews

---

## 🤝 Contributing

Contributions are welcome! Feel free to:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

MIT License - feel free to use this project for learning or personal use!

---

## 🙏 Acknowledgments

- **Netflix** - UI/UX inspiration
- **TMDB** - Movie data and API
- **Firebase** - Authentication and backend services

---

## 🔗 Links

- **Repository**: [github.com/SergioSediq/netflix-clone](https://github.com/SergioSediq/netflix-clone)
- **TMDB API**: [themoviedb.org/documentation/api](https://www.themoviedb.org/documentation/api)
- **Firebase**: [firebase.google.com](https://firebase.google.com)

---

**Built with 🎬 by Sergio Sediq**

*Disclaimer: This is a clone project for educational purposes only. Not affiliated with Netflix.*


