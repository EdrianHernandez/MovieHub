# MovieHub 🎬

MovieHub is a sleek and intuitive movie discovery platform built with React that helps users find their next favorite movie without the hassle. With real-time search capabilities and trending movie insights, users can easily explore and discover movies that match their interests.

## ✨ Features

- **Smart Search**: Real-time movie search with debounced API requests for optimal performance
- **Trending Movies**: Track and display popular movie searches powered by Appwrite backend
- **Modern UI**: Clean and responsive interface with beautiful gradients and animations
- **Comprehensive Movie Details**: Easy-to-read display of movie information including:
  - Movie posters and titles
  - Release dates
  - Ratings and reviews
  - Original language

## 🛠️ Tech Stack

- **Frontend Framework**: React + Vite
- **Backend Service**: Appwrite
- **API Integration**: TMDB (The Movie Database)
- **UI Components**: Custom-built React components
- **State Management**: React Hooks

## 🚀 Getting Started

1. **Clone the repository**
```sh
git clone https://github.com/yourusername/MovieHub.git
cd MovieHub
```

2. **Install dependencies**
```sh
cd movie-hub
npm install
```

3. **Configure Environment Variables**
Create a `.env` file in the movie-hub directory with:
```env
VITE_TMDB_API_KEY=your_tmdb_api_key
VITE_APPWRITE_PROJECT_ID=your_appwrite_project_id
VITE_APPWRITE_DATABASE_ID=your_appwrite_database_id
VITE_APPWRITE_COLLECTION_ID=your_appwrite_collection_id
```

4. **Start the development server**
```sh
npm run dev
```

## 📝 Environment Setup

1. Get your TMDB API key from [TMDB website](https://www.themoviedb.org/documentation/api)
2. Set up an Appwrite account and create a new project
3. Configure your Appwrite database and collection
4. Add the required environment variables

## 💡 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

---
Built with ❤️ using React and Appwrite
